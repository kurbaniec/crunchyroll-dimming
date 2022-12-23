<h1 align="center">
  <br>
  <code>crunchyroll-dimming</code> ৻(•̀ ᗜ •́ ৻)
  <br>
</h1>


<h4 align="center">Remove screen dimming effect in Crunchyroll.</h4>

## 🛠️ Build

### Chrome

```bash
npm run build:chrome
```

### Firefox

```bash
npm run build:firefox
```

As Firefox requires extension to be signed, one needs to create a developer account. See [here](https://stackoverflow.com/a/59172713) for more information. After obtaining credentials, run the following command. Replace `api-key` & `api-secret` with your details.

```bash
npm run build:firefox && unzip -o builds/crunchyroll-dimming-firefox.zip -d builds/crunchyroll-dimming-firefox && web-ext sign --api-key="<your user>" --api-secret="<your secret>" --source-dir=builds/crunchyroll-dimming-firefox --artifacts-dir=builds
```

## 💻 Install

### Chrome

Pull package from `builds\crunchyroll-dimming-chrome.zip` into `chrome://extensions/` window in developer mode.

### Firefox

Pull package from `builds\<hash>-0.0.1.xpi` into ` about:addons` window.

## ⭐ Sources

* https://github.com/ThomasTavernier/Improve-Crunchyroll/tree/firefox
* https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension











