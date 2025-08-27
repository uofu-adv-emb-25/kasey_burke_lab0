# Kasey and Burke Lab0 Environment
The lab utilizes a template repository with code causing 
the led on the Rasberry PI to blink. The frequency of the blink
was increased by decreasing the value inside a task delay.

![Lab0 Workflow](https://github.com/uofu-adv-emb25/kasey_burke_lab0/actions/workflows/main.yml/badge.svg)

# Renode setup
The Raspberry Pico needs configuration files for Renode to work properly.

* On MacOS, the installation location is `/Applications/Renode.app/Contents/MacOs`
* On Linux, the location for Debian, Fedora, and Arch is `/opt/renode`
* On Windows, the location is `C://Program Files/Renode`

To add the Pico configuration files:
1. Copy `rp2040_spinlock.py` and `rp2040_divider.py` to the `scripts/pydev` directory of your Renode installation.
1. Copy `rpi_pico_rp2040_w.repl` to the `platforms/cpus` directory.
