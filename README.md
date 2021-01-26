# FirefoxCSS-Store
<p align="center">A collection site of Firefox userchrome themes, mostly from FirefoxCSS Reddit. <a href="https://firefoxcss-store.github.io/">Preview here.</a></p>

## Generic Installation

+ Go to the wanted theme and click the download button.
+ You should now be on the github page for that topic.
+ Below you should see a guide on how to install that particular theme and a few preview pictures. Anyway, here are some common steps for all themes.

1. Download theme with the big green button "Code" >> Download.zip
2. Open `about:config` page.
3. A dialog will warn you, but ignore it, ~~just do it~~ press the `I accept the risk!` button.
4. Search for these:

	+ **`toolkit.legacyUserProfileCustomizations.stylesheets`**
	+ **`layers.acceleration.force-enabled`**
	+ **`gfx.webrender.all`**
	+ **`gfx.webrender.enabled`**
	+ **`layout.css.backdrop-filter.enabled`**
	+ **`svg.context-properties.content.enabled`**

	Then make sure to **enable them all!**.

5. Go to your Firefox profile.

	+ Linux - `$HOME/.mozilla/firefox/XXXXXXX.default-XXXXXX/`.
	+ Windows 10 - `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`.
	+ macOS - `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX`.

6. Create a folder and name it **`chrome`**, then assuming that you already have cloned this repo, just copy the theme to `chrome` folder.
7. Restart Firefox.

## Add your theme <3

1. If you have a Github account:
  1. Fork this repository.
  2. Look for a file called `themes.json`, open and edit it.
  3. Add a comma `,` right after the last **curly bracket }**.
  4. Copy the [following code](###Code) and paste it in the file.
  5. Add the properties of your theme: **title**, **link**, **description** and **image**.
  6. Send it as a pull request in the repository.
2. If you have a Twitter account:
  1. Send **at least** the following properties: **picture**, **link** to [@Neikon66](https://twitter.com/Neikon66). 

### Code

```
{
		"title": "..........",
		"link": "..........",
		"description": "..........",
		"image": ".........."
}
```

# What you think =?

<p align="center">Feel free to send me any feedback via issue or my twitter [@Neikon66](https://twitter.com/Neikon66).</p>
