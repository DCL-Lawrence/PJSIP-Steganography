# PJSIP-Steganography
## Introduction
This is an extension for <a href="https://www.pjsip.org/">PJSIP</a> project. You can use these codes to implement the real-time secret data transmission with internet low bit rate codec (iLBC).
## Usage
<ol>
  <li>Add "#define PJ_LOG_MAX_LEVEL 0" into "config_site.h".</li>
  <li>Copy "pjsua_app_legacy.c", "iLBC_encode.c" and "iLBC_decode.c" into the project.</li>
  <li>Activate "--no-tcp" and "--add-codec=ilbc/8000" options while starting.</li>
  <li></li>
</ol>
