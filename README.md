# Install R in VSCODE


安装VSCdebugger报错：package 'vscDebugger' not installed because it is not built for UCRT

A workaround is to build it from source using R 4.2 on Windows.

The error relates to the UCRT runtime that is used starting from version 4.2 to support native UTF-8 encoding for Windows.

install.packages('https://github.com/ManuelHentschel/vscDebugger/files/9231784/vscDebugger_0.4.7.zip', repos = NULL, type = "win.binary")


# Using Github in VSCODE
Error：

fatal: unable to access 'https://github.com/xlong0215/MyTest20220926.git/': Failed to connect to github.com port 443 after 21107 ms: Timed out

（科学上网）

