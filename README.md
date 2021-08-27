# libxevd

The version of libxevd library prepared in a way to be able to include it into the third_party tree of the webrtc project and then use by webrtc

## Cloning project with submodules

Clone this repository into **third_party** directory of **webrtc** project (https://webrtc.googlesource.com/src.git). <br>
In case of using **webevc_internal** repository (https://github.sec.samsung.net/RD-ADMEDIA/webevc_internal) destination path should look like follows: **webevc_internal/src/third_party** 

> Use the following command to clone repository and do not forget to pass **--recurse-submodules** to the git clone command, to automatically initialize and update submodule in the repository.

```bash
git clone --recurse-submodules https://d.kozinski@github.sec.samsung.net/d-kozinski/libxevd.git
```
