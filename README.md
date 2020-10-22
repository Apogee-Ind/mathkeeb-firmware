# Apogee Industries Mathkeeb - Firmware Source Code
This repository includes all the necessary files to recompile, modify, or create firmware .hex files compatible with the Apogee Industries Mathkeeb.

## General Info
You can find the latest releases under the 'Releases' tab on the right. This includes stable (tested) releases, prereleases (version numbers such as v1.1-pre1, v1.1-pre2), beta versions, and other releases. These contain .hex files as well as the source code (at time of release) packaged as .zip or .tar.gz archives.

You are welcome to clone/fork this repository, and to submit pull requests with your own additions/changes for review. Our team will review your changes and potentially incorporate them into the next release. In particular, assistance with localization (such as for different keyboard languages/regions) and with addition of layers/macros for as-yet unsupported programs would be welcome.

## Changelog
For complete changelogs, see the release notes for a given release. The `master` branch will always be kept inline with the most recent stable release. Any unreleased changes will only be found on the `snapshot` branch, or any similar branches on forked repositories. 

## TODO before version 1.1 release
1. add `dot(` to MATLAB layer as `2nd + *`
2. add `zeros(` to MATLAB layer as `2nd + z`
3. add `np.zeros(` to Python layer as `2nd + z`
4. add `\Sigma` to LaTeX layer as `2nd + Sigma`
5. add `\Pi` to LaTeX layer as `2nd + Pi`
4. update linux firmware to parity with Windows version
5. update no-parentheses firmware to include new macros and keybinds
6. rewrite desmos firmware to eliminate extra layers and macros to save space

## License
**GNU General Public License (GPL) version 2.** You are free to download, copy, modify, and redistribute the files contained in this repository. 
**NOTE:** Third-party libraries such as LUFA, PJRC, and V-USB have their own respective licenses.

The source code here was originally cloned from the TMK Keyboard Firmware source code, however it may not be entirely up-to-date with that library. We plan to eventually migrate fully to a QMK-based solution, complete with inclusion in that library's package management database (so you will be able to compile and download Mathkeeb firmware using the QMK website's tool). 


