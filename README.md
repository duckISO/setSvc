# setSvc
An interactive and customisable replacement for `sc config`, which can configure any service/driver, unlike `sc config`.

`sc config` is not able to configure the startup type for every service/driver, some services/drivers always output an 'Access denied' error.

**Download:** https://raw.githubusercontent.com/duckISO/setSvc/main/setSvc.cmd (right click -> 'Save as')

## Features
- An interactive option, where it will prompt the user about configuring a service
- Automatic elevation to TrustedInstaller (if avaliable) or regular admin (`/q` argument only)
- Checking whether the service/driver exists or not, and other error detection
- Option to attempt to stop the service/driver being configured
- Ability to use it as a function in scripts (use `call (setSvc.cmd path here) "(service)" "(start)" /f`)
- Help menu

https://user-images.githubusercontent.com/65787561/204135772-a8b7957c-03b3-476c-b4f8-54eb29737c56.mp4
