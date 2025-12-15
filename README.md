# Civitai Helper
Stable Diffusion Webui Extension for Civitai, to handle your models much more easily.

# Features
* Scans all models to download model information and preview images from Civitai.
* Link local model to a civitai model by civitai model's url
* Download a model(with info and preview) by Civitai Url into SD's model folder or subfolders.
* Downloading can be resumed if an issue occurs, which is good for large files.
* Checking all your local models for new versions from Civitai
* Download a new version directly into SD model folder (with info and preview)
* Modified Built-in "Extra Network" cards, to add the following buttons on each card:
  - 🖼️: Modified "replace preview" text into this icon
  - 🌐: Open this model's Civitai url in a new tab
  - 💡: Add this model's trigger words to prompt
  - ✏️: Rename model
  - ❌: Remove/Delete model
* Option to always show additional buttons, to help with touchscreens.
* To the best of my knowledge, this extension should still work in versions of webui prior to v1.5.0, but it is not tested. I make best-effort attempts to write code that *should* maintain compatibility with older versions, but if you have run into problems, please file an issue and I'll attempt to resolve it.
* **New feature**: Automatically add metadata of model resources used to all generated images. Useful for uploading to Civitai. More information below.

# Install
Go to SD webui's extension tab, go to `Install from url` sub-tab.
Copy this project's url into it, click install.

Alternatively, download this project as a zip file, and unzip it to `Your SD webui folder/extensions`.

Everytime you install or update this extension, you need to shutdown SD Webui and Relaunch it. Just "Reload UI" won't work for this extension.

Some functionality from Civitai, like downloading models, requires having an account and adding your API key.


### [Changes](https://github.com/SiliconeShojo/Stable-Diffusion-Webui-Civitai-Helper/blob/master/CHANGELOG.md)
