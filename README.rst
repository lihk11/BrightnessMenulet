Brightness Menulet
==================

**This tool is not stable and almost not maintained. Use at your own risk. Try to look at forks, there's a chance your LCD model might be supported**

Allows you to control monitor brigthness via menu in status bar.

This tool works on OSX 10.8+. If you have tested your monitor(s) with this tool, please
let me know wether it worked or not so I can add monitor models here. Preference's Debug button logs to the
console VCP codes and their values on the selected monitor.

Download app build: `Brightness.Menulet.zip`_.

.. _BrightnessMenulet.zip:
    https://github.com/lihk11/BrightnessMenulet/releases/download/v1.4/Brightness.Menulet.zip

**I have made some modification of very original code and make the code works for my dell u2414h and u2718q.**

**If you have tested your monitor(s) with this version of tool, please let me know whether or not it work and I will update this table.**

Monitors:
.......................
+------------------+---------------+
| Working          | Non-Working   |
+==================+===============+
| Dell U2414H      |               |
+------------------+---------------+
| Dell U2718Q      |               |
+------------------+---------------+
| HP E272q         |               |
+------------------+---------------+





Features:
............

- Following the internal Display's Brightness (if automatic brightness is activated in the system preferences this follows the light sensor as well)
- Auto-Follow is indicated by highlighting the status bar icon
- Multi-Monitor support (no limit to amount of monitors)!
- Key bindings for Darker, Brighter and toggle the Follow-Main-Screen option
- Compatible with OSX 10.8+

Roadmap:
........

- Support for other monitor makes (Currently only tested on Dell and certian HP displays)
- Time based settings
- Fading between Auto-Follow values

Credits:
........

- `Alec Jacobson`_ - `original Brightness Menulet app`_ creator
- Jon Taylor - `DDC/CI bindings`_
- Victor Miroshnikov - copy&paste&debug job
- `Joey Korkames`_: EDID Reading

.. _DDC/CI bindings:
    https://github.com/jontaylor/DDC-CI-Tools-for-OS-X

.. _Alec Jacobson:
    http://www.alecjacobson.com/weblog/

.. _Joey Korkames:
    https://github.com/kfix/ddcctl

.. _original Brightness Menulet app:
    http://www.alecjacobson.com/weblog/?p=1127
