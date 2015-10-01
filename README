# Making Freelancer Pretty
Follow these directions to get a fully-functional, optimized install of Freelancer running on your machine.
This setup will enable wide-screen resolutions, increase draw distances, and generally make the vanilla
game more beautiful.  This setup does not include the game itself.  You must provide your own installation
media.

Everything in this guide was tested in Windows 10.

## Installing Freelancer
* Install game using `game cd\setup.exe`
* Copy the no-cd cracked `Freelancer.exe` to `install-location\EXES`
    * Note that there are a few varients that will increase draw distance.  The game is near-sighted out of the box.

## Enabling Wide-Screen
* To enable 1080p, copy `PerfOptions.ini` to `My Documents\My Games\Freelancer`
* To enable wide screen field of view (80 degrees) and fix broken fonts, copy `\wide-screen\DATA` to `install-location`

Note:  To run at another resolution, such as 720p or 4K, edit the `PerfOptions.ini` and change the line near
the bottom that reads `size= 1920, 1080` to whatever resolution you want.

Note:  To change your field of view, edit `install-location\DATA\cameras.ini`.

##### A Note on Resolution
Launching the game from a desktop running at a different resolution may cause your game resolution to reset 
to 800x600.  This can be fixed by re-copying `PerfOptions.ini` to `My Documents\My Games\Freelancer`.  Be sure to
set your resolution to the resolution specified at the bottom of `PerfOptions.ini` prior to launching the game.

## Enabling Anti-Aliasing (NVIDIA Only)
The game looks much better with anti-aliasing enabled.  You can force anti-aliasing by overriding the application
settings in the NVIDIA Control Panel.

Note: Options will vary depending on your video card.  These options are just guidelines.

* Launch the NVIDIA Control Panel
* Go to `3D Settings -> Manage 3D settings`
* Select the `Program Settings` tab
* Select `Freelancer (freelancer.exe)` from the `Select a program to customize` dropdown
    * If you can't find Freelancer in the drop down, click the `Add` button and locate it
* In the `Specify the settings for this program` area, set the following:
    * Anisotropic filtering: `16x`
    * Antialiasing - FXAA: `On`
    * Antialiasing - Gamma correction: `On`
    * Antialiasing - Mode: `Override any application setting`
    * Antialiasing - Setting: `32x CSAA`
    * Antialiasing - Transparancy: `8x (supersample)`
    * Texture filtering- Anisotropic sample: `On`

## Disabling Movies
* To disable intro movies delete one or more of the files in the `install-location\DATA\MOVIES` directory
    * It is also OK to remove the directory entirely

## Faster Cruise Speed
To increase cruise speed from 300 to 500, put the `constants.ini` file in `install-location\DATA`.
You can edit this file with a binary ini editor if you want to change the cruise speed.  (Be aware, making it
ultra-fast will mess up auto-pilot and AI.)

## Editing "Binary" ini Files
Some (many) of thie .ini files appear garbled in a text editor and must be edited using a bin ini editor.
There is one included here `archived-biniedit.zip`.  Note - I didn't write this.
Download:  http://the-starport.net/search.php?query=bini&mid=13&action=showall&andor=AND

## Other Modules
There are a few other modules that may improve the playability of vanilla FreeLancer.  I didn't write them.
I've included links to the originals.

#### Fix HUD positions
To fix your cockpit HUD to conform to a widescreen layout, install HudShift.

The download can be found here:  https://mega.nz/#!yE8xGTJB!IC7HiWVyGFmO2xLrJdyGQHTdUx9daMbYyQTNRRxbveE

#### High-resolution textures - new sounds: The Swag Pack
If you want higher resolution textures, consider installing the swag pack.

Details are here:  http://discoverygc.com/forums/showthread.php?tid=98156

Note:  This will make objects in the game (ships, stations) appear much darker.

## Known Issues
Some or all of the menus may be in odd locations when you first load the game.  This goes away once you launch
to space.  The only time this is really bad is when you do not have the icon to launch to space and the top menu
bar is hidden (above the top of the screen).  (i.e. Before your first mission.)  I don't know of a work-around
to this.