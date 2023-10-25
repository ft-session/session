# session
Session is a tool designed to help you achieve your logtime objectives.

### Install session
```sh
curl -sL https://github.com/ft-session/session/releases/latest/download/install.sh | sh
```
---
### Use session
There are three modes:
* `at` will disconnect you at the specified time.
```sh
session -at 9:00   # This will disconnect you at 09:00
```
* `in` will disconnect you after a certain amount of time.
```sh
session -in 3:00   # This will disconnect in 03:00 from now
```
* `inf` will never disconnect you.
```sh
session -inf       # Best to use only in emergencies
```
