# ttypipe

Remote control for your TTYs.

ttypipe pipes any data it receives from stdin straight through to the tty's input buffer (by way of the `TIOCSTI` ioctl).

For convenience, ttypipe will also switch the controlling terminal into raw mode to receive input if it's running under a TTY itself.

### Installation

```
# make install
```