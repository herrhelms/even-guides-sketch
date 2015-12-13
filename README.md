# Evenly distributed Guides
This is a Plugin for [Sketch App](http://www.sketchapp.com) that adds guides to a selected artboard.
For the magic to shine you need to have the *Ruler* visible. `Crtl+r`

## Installation
Install this plugin via [Sketch Toolbox](http://sketchtoolbox.com) or download the package manually into to your Sketch3 Plugin Folder. The path should resemble the following
```.../com.bohemiancoding.sketch3/Plugins/even-guides-sketch-master``` **Tipp:** The .sketchplugin file should to reside in a directory!

Select any artboard you have, or if not, go ahead and create one. Then either goto the Plugins Menu and select `Evenly Distributed Guides -> Distribute Guides` or use Keyboard shortcut
`Cmd + alt + g`. A modal window will appear where you can define the setup for the guides you aim to create.

## Yes, I know...
**Within Sketch there's a specific feature for Layout Settings** where you can define any rows and columns. It's very powerful and substantial but I find it a little too dificult to maintain.
My approach is a little different:

Sometimes you just need to setup a grid or raster real fast, but precise. And once everything is at it's place. You can get rid of all these guides again.
So, columns and/or rows with an optional gutter should do. Optionally, when using a gutter you're able to specify if you want to begin and end with a gutter or column & row.
Just as fast as you can generate the helping guides, it's possible to remove them again. keyboard shortcuts are really helpful here.

 - `Cmd + alt + g` - Show the Modal for generation (Setup)
 - `Cmd + alt + r` - Removes all guides (After confirmation)
 - `Crtl+r` - Toogle Ruler visibility (shows or hides guides too)

## With a little help from my friends
While the actual magic is all done by myself, I *stole* a couple of tiny helper functions related to artboard selection from [Nadav Savio](https://github.com/nadavsavio/sketch-plugins)'s Sketch-Plugins. Great work, hope you don't mind.

### That's all folks
This is my second Sketch Plugin, so please feel free to [contact me](http://bit.ly/1MSRFbd) via twitter for comments, suggestions and critique.
If you like this plugin consider giving this repository a star! If you're owning Bitcoin feel free to send some satoshis: `1BoFajaVNQ5Z8a3E7ZQvt8sWyTCGrxRtS9`.
Oh and btw: You can fork and contribute to the code and extend this package. I will happily merge any tested PRs.
