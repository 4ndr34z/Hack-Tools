<div align="center">
  <img alt="logo_hack_tools" src="https://i.postimg.cc/GtLdZ2rZ/noun-Panama-hat-1454601.png" />
  <h1>Welcome to HackTools 🛠</h1>
  <p>
    <img alt="Version" src="https://img.shields.io/badge/version-0.3.8-blue.svg?cacheSeconds=2592000&style=for-the-badge" />
    <img alt="release" src="https://img.shields.io/github/v/release/LasCC/Hack-Tools?color=yellow&style=for-the-badge" />
    <a href="https://addons.mozilla.org/en-US/firefox/addon/hacktools" target="_blank">
      <img alt="mozilla" src="https://img.shields.io/amo/v/hacktools?color=purple&label=mozilla%20addons&logo=mozilla&style=for-the-badge" />
    </a>
    <a href="https://chrome.google.com/webstore/detail/hack-tools/cmbndhnoonmghfofefkcccljbkdpamhi?hl=en" target="_blank">
      <img alt="chrome-extension" src="https://img.shields.io/chrome-web-store/v/cmbndhnoonmghfofefkcccljbkdpamhi?style=for-the-badge" />
    </a>
    <img alt="Downloads" src="https://img.shields.io/github/downloads/LasCC/Hack-Tools/total.svg?style=for-the-badge" />
    <img alt="commit" src="https://img.shields.io/github/last-commit/LasCC/Hack-Tools?style=for-the-badge" />
    <a href="https://inventory.rawsec.ml/" target="_blank">
      <img alt="RawSecInventory" src="https://inventory.raw.pm/img/badges/Rawsec-inventoried-FF5050_for-the-badge.svg" />
    <a/>
    <img alt="stars" src="https://img.shields.io/github/stars/LasCC/Hack-Tools?style=social" />
    <a href="https://lgtm.com/projects/g/LasCC/Hack-Tools/context:javascript">
      <img alt="Language grade: JavaScript" src="https://img.shields.io/lgtm/grade/javascript/g/LasCC/Hack-Tools.svg?logo=lgtm&logoWidth=18"/>
    </a>
  </p>
  <p align="center">
    <a href="#the-all-in-one-red-team-browser-extension-for-web-pentesters"><b>Introduction</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#preview"><b>Preview</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#install-the-extension"><b>Install</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#build-from-source-code"><b>Build</b></a>
    &nbsp;&nbsp;&mdash;&nbsp;&nbsp;
    <a href="#show-your-support"><b>Support</b></a>
  </p>
</div>

### The all-in-one Red Team browser extension for **Web Pentesters**

HackTools, is a web extension facilitating your **web application penetration tests**, it includes **cheat sheets** as well as all the **tools** used during a test such as XSS payloads, Reverse shells and much more.

With the extension you **no longer need to search for payloads in different websites** or in your local storage space, most of the tools are accessible in one click. HackTools is accessible either in **pop up mode** or in a whole tab in the **Devtools** part of the browser with F12.

### Enhancements
- Added my PS Revshell
- Added base64 encoding of PS revshell
- Added base64 encoding of Netcat revshell
- Added Integer and Hexadecimal convertion of IP.
- Added a LOLBAS and GTFOBins pane
- Some other minor additions

### Current functions

- Dynamic Reverse Shell generator (PHP, Bash, Ruby, Python, Perl, Netcat)
- Shell Spawning (TTY Shell Spawning)
- MSF Venom Builder
- XSS Payloads
- Basic SQLi payloads
- Local file inclusion payloads (LFI)
- Base64 Encoder / Decoder
- Hash Generator (MD5, SHA1, SHA256, SHA512, SM3)
- Useful Linux commands (Port Forwarding, SUID)
- RSS Feed (Exploit DB, Cisco Security Advisories, CXSECURITY)
- CVE Search Engine
- Various method of data exfiltration and download from a remote machine

## Preview

<div align='center'>
  <img alt="preview_1" src="https://raw.githubusercontent.com/4ndr34z/Enhanced-Hack-Tools/master/eht.png" />
</div>
<br>
<div align='center'>
  <img alt="preview_2" src="https://raw.githubusercontent.com/4ndr34z/Enhanced-Hack-Tools/master/eht2.png" />
</div>

<div align='center'>
  <img alt="preview_3" src="https://i.imgur.com/wJr1xYX.png" />
</div>

<div align='center'>
  <img alt="preview_4" src="https://i.imgur.com/bh896v1.png" />
</div>

<div align='center'>
  <img alt="preview_5" src="https://i.imgur.com/dMvkn0g.png" />
</div>




You can build the project yourself from the source code

<h2> 
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/firefox.svg" alt="firefox_icon" title='Firefox' width="25" height="25" style="float:left;" /> 
  Mozilla Firefox
</h2>



<h2> 
  <img src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/safari.svg" alt="safari_icon" title='Safari' width="25" height="25" style="float:left;" /> 
  Instructions to build for Safari
</h2>

Create a safari web extension project using the command below. *This is to be run once.*

```bash
/Applications/Xcode.app/Contents/Developer/usr/bin/safari-web-extension-converter dist
```

Follow the instructions to create the project the default language should be Swift.

- Build project.
- Open Safari and enable unsigned extensions; Develop -> Allow Unsigned Extensions.
- Open Safari -> Preferences -> Extensions and enable Hack-Tools
- Click on the extension icon and switch to full screen mode.

*Instructions provided by [jayluxferro](https://github.com/LasCC/Hack-Tools/issues/88)*

### Build from source code

```bash
git clone https://github.com/4ndr34z/Enhanced-Hack-Tools
cd Enhanced-Hack-Tools
npm install && npm run build     # If you have installed yarn you can replace npm with yarn
```

Once the build is done correctly, webpack will create a new folder called **dist**

After that you need to go to the **extension** tab on your chrome based navigator and turn on the **developer mode**

<img alt="extension_tutorial" src="https://i.imgur.com/0GRfu2K.png" />

Then click on the **load unpacked** button in the top left corner

<img alt="extension_tutorial" src="https://i.imgur.com/q41GeAb.png" />

Once you clicked on the button you just need to select the **dist folder** and that's it ! 🎉

<img alt="extension_tutorial" src="https://i.imgur.com/mL4TVu0.png" />

## Authors

👤 <a href="http://github.com/LasCC" alt="Github_account_Ludovic_COULON">**Ludovic COULON**<a/> & <a href="http://github.com/rb-x" alt="Github_account_Riadh_BOUCHAHOUA">**Riadh BOUCHAHOUA**<a/>

## Show your support

You can give a ⭐️ if this project helped you !

Note that this project is maintained, developed and made available for **free**, you can offer us a coffee, it will be very **encouraging and greatly appreciated** 😊

<a href="https://www.paypal.me/hacktoolsEXT" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important"></a>
