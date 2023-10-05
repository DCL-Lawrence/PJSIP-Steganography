# PJSIP-Steganography
## Introduction
This is an extension for <a href="https://www.pjsip.org/">PJSIP</a> project. You can use these codes to implement the real-time secret data transmission with internet low bit rate codec (iLBC).
## Usage
<ol>
  <li>Add "#define PJ_LOG_MAX_LEVEL 0" into "config_site.h".</li>
  <li>Copy "pjsua_app_legacy.c", "iLBC_encode.c" and "iLBC_decode.c" into the project.</li>
  <li>Activate "--no-tcp" and "--add-codec=ilbc/8000" options while starting.</li>
  <li>Use "&" notation to input the secret message.</li>
</ol>

### File path
<ol>
  <li>config_site.h: \pjproject-2.xx\pjlib\include\pj</li>
  <li>pjsua_app_legacy.c: \pjproject-2.xx\pjsip-apps\src\pjsua</li>
  <li>iLBC_encode.c: \pjproject-2.xx\third_party\ilbc</li>
  <li>iLBC_decode.c: \pjproject-2.xx\third_party\ilbc</li>
</ol>
