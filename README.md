# MARP Themes - `marpstyle` ![](https://camo.githubusercontent.com/83d3746e5881c1867665223424263d8e604df233d0a11aae0813e0414d433943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)

Marp themes repository, created to as a simple way to create re-usable themes across multiple sets of slides for notes, presentations etc. Based on a similar repository by [Paulo Cunha](https://github.com/cunhapaulo/marpstyle) this repository started as a fork of that.  My motivation is to store a few simple modifications of the ```default``` Marp template for my teaching materials.   

## What is Marp? 

- Marp allows the creation of presentations using Markdown, lightweight and text based it can be authored almost any device and works well with version control. 

- Please see [Paulo's original repo](https://github.com/cunhapaulo/marpstyle) for more details, alternatively the pages of the [Marp Team](https://github.com/marp-team). 

## Available Themes

List of themes. 

### ![](./img/my-theme.png) First theme - simple modification to default. 
  [![Style: Notes1](./img/examples-my-theme.png)](./examples/example-my-theme.pdf)


<br>

# How to Use

For this selection of themes `Marp` must be installed and operational. These themes have been created and tested with Visual Studio Code usage in mind, the instructions below are based on those in [Paulo's original repo](https://github.com/cunhapaulo/marpstyle) I've included them here as a reminder. 

1. Paulo suggests that you create a separate folder for each presentation you intend to create. Inside this presentation folder he also recommends you to create another folder, which might be called `/style`, specifically designated for the `CSS` style files you intend do use in your presentation.

2. ~~A prerequisite for using some extra fonts is that you have them installed on your computer. That said, some of the `styles` available here require special fonts not available by default in most OS installations. I intend to make some modifications so that these fonts are automatically downloaded from internet, but until this modification ins implemented, you will find below a section containing informations about the special fonts use in some of my styles and a possible locations where from you can download them (for free).~~  I plan on making only minor changes. 

3. Setup with VS Code. 

## VS Code:

Two ways to use styles, locally or from the internet.  My motivation for this repo was to create a library of my own styles online (to avoid copying the files around,) so I'm going to use the latter. I'm including Paulo's original documentation (with some edits) for completeness. 

### Local files:

To use local copies of these files include the path to the theme files (`CSS` files) in your `workspace.code-workspace` in order to make them available to your slide deck. 

<br>

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.marp.themes": [
			"./style/notes1.css"
		]
	}
}
```

### Remote (internet) styles:

You might as well use themes directly from github using the url, just like depicted below:

```json
{
	"folders": [
		{
			"path": "."
		}
	],
	"settings": {
		"markdown.marp.themes": [
			"https://smu-sc-gj.github.io/style/notes1.css"
		]
	}
}
```

<br>

# Credits

- [Paulo Cunha](https://github.com/cunhapaulo/marpstyle) produced a much more complete library of styles, this repo is a cut down copy with some basic styles for my class materials. 
