﻿# SetExceptionBPX

Set an exception breakpoint. If an exception breakpoint is active, all the exceptions with the same chance and code will be captured as a breakpoint event and will not be handled by the default exception handling policy.

## arguments

`arg1` Exception name or code of the new exception breakpoint

`[arg2]` Chance. Set to 1 to capture first-chance exceptions, 2 to capture second-chance exceptions, 3 to capture all exceptions. Default value is 1.

## result

This command does not any result variables.
