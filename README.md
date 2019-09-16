# ffe
Frida function enumeration and injection framework. Code is based on https://github.com/yairp7/basic-frida

Current script requires manual modifications, read the comments :)

To use:
1. Install frida-server and frida-tools (a good guide can be found here: https://omespino.com/tutorial-universal-android-ssl-pinning-in-10-minutes-with-frida/)

2. modify the agent.js to monitor the functions you need
2.b. adjust accordingly in the pyFrida.py script

3. python pyFrida.py
