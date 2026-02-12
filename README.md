# Logger Library for PeTTa

## Overview

Logger library for PeTTa to log timestamped messages into a file at
various log levels.

## Usage

### Import

To import the logger library, invoke `git-import!` as follows:

```scheme
!(git-import! "https://github.com/ngeiswei/petta_lib_logger" "swipl pack install log4p")
```

### Methods

The methods of the logger are:

- `logger-filepath`: get filepath
- `logger-stdout`: get stdout flag
- `logger-timestamp`: get timestamp flag
- `logger-set-filepath`: set filepath
- `logger-set-stdout`: set stdout flag
- `logger-set-timestamp`: set timestamp flag
- `logger-level`: get log level
- `logger-levels`: get all possible log levels
- `logger-set-level`: set log level
- `logger-log`: log message at the given level
- `logger-trace`: log message at the trace level
- `logger-debug`: log message at the debug level
- `logger-info`: log message at the info level
- `logger-warn`: log message at the warn level
- `logger-error`: log message at the error level
- `logger-fatal`: log message at the fatal level
- `logger-logf`: log formatted message at the given level
- `logger-tracef`: log formatted message at the trace level
- `logger-debugf`: log formatted message at the debug level
- `logger-infof`: log formatted message at the info level
- `logger-warnf`: log formatted message at the warn level
- `logger-errorf`: log formatted message at the error level
- `logger-fatalf`: log formatted message at the fatal level

### Examples

Usage examples can be found in [logger_example.metta](logger_example.metta).
