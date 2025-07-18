# pq-wallet

This project is currently in development and not yet ready for production use.

## Loading Your Extension in Firefox Nightly

To get your extension running in Firefox Nightly, you'll need to follow a few simple steps since you're working with an unsigned extension.

**Open Firefox Nightly:** Type `about:config` in the address bar and navigate there. You'll need to disable Firefox's signature requirement for extensions, so search for `xpinstall.signatures.required` and set this value to `false`. This allows you to install unsigned extensions during development.

**Load the extension:** Navigate to `about:addons` to access the Add-ons Manager. Look for the gear icon \(⚙️\) and click on it to open the options menu. Select "Install Add-on From File..." from the dropdown menu.

Browse to your extension's `.zip` file and select it. Firefox will prompt you to confirm the installation - click "Add" and then "Ok" when the popup appears in the top right corner. Your extension should now be loaded and ready to use.

# Schematic Step-by-Step Loading Instructions

1. **Open Firefox Nightly**

2. **Disable signature requirement:**
  - Navigate to `about:config`
  - Search for `xpinstall.signatures.required`
  - Set to `false`

3. **Load the extension:**
  - Navigate to `about:addons`
  - Click on the gear icon ⚙️
  - Click "Install Add-on From File..."
  - Select your extension's `.zip` file 
  - Click on "Add" and then "Ok" on the top right popup
