# Cyberpunk-CUI-Foobar2000-Theme
A dark Cyberpunk Theme for Columns UI Foobar2000. Focused on a clean dynamic look with switchable tabs while utilizing several community components and scripts. 


![Animation7](https://github.com/user-attachments/assets/e06f9760-af55-4097-9a1d-575f4d9759cd)

![Animation788756-ezgif com-optimize](https://github.com/user-attachments/assets/8937725c-9e53-47d6-a026-4671add21d0a)


## Index 
### Download
- [Download Theme](#download-theme)

### Step by Step guidance (New users Start here):
1. [Install Foobar](#initial-install)
  
2. [Download Components](#download-components)

3. [Install Components](#installing-components)

4. [Install Packages](#preparing-biography-and-library-tree-packages)
  
5. [Importing Theme](#importing-theme)

6. [Icon Downloads](#icons-waveform-control-panel-fixes)
  
7. [Adjusting Waveform Minibar](#waveform-minibar)

8. [Final Adjustments/Divider](#final-touches)

### Import Theme:

- [Installation Instructions](#importing-theme)  (Just show me how to import the theme)

### Tips/How To:
- [Cover Panels](#cover-main-view-usage)
- [Right Panels](#right-side-panel)
- [Left  Panel](#left-panel)
- [Center Panel](#main-center-panel)
- [Editing your Theme/Add your own panels](#editing-themeadding-your-own-panels-or-scripts)
- [Hotkeys/Shortcuts](#hotkeysshortcuts)
  
### Scripts By Me Usage:
- [Playlist Cover Tab Manager](#playlist-cover-tab-manager)
- [Dynamic Image Panel](#dynamic-image-panel-main)

## Download Theme
- Click on the `theme` folder in the repo.
- Click on the fcl file

<img width="876" height="385" alt="image" src="https://github.com/user-attachments/assets/7a737dae-24e1-423c-97be-efa804cc469c" />

- Download raw file

<img width="256" height="137" alt="image" src="https://github.com/user-attachments/assets/0488e724-3216-4380-a869-a10cdc9e5f8c" />

- Ready for importing!

### Initial install
- I will be showing you how to install this theme on a completely fresh install.
- First, download foobar from https://www.foobar2000.org/windows

<img width="400" height="206" alt="image" src="https://github.com/user-attachments/assets/d368aa59-2b9f-4e16-bf7a-6deefd1b2fa8" />
  
- Select 32bit verison


<img width="400" height="305" alt="image" src="https://github.com/user-attachments/assets/c69a9422-f5bb-4785-abd4-b270fe28d697" />

- Portable installion but either is fine

  
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/91ba12df-7557-43f0-86e0-b2acd437ef77" />

- Select full, do not change
- Hit install


<img width="400" height="389" alt="image" src="https://github.com/user-attachments/assets/56200ab3-cc86-4a98-a33e-550cda131af7" />

- Ignore the quick setup and just hit OK

### Download Components 
- Components in foobar are basically added functionality that you can add to your theme. You must download these for this theme to properly work. 
- First create a folder like, 'fbComponents' to keep all of the components organized and in one place for an easy install.
- It may look like much but once you finish installing, the 'hard' part is basically over!
- Simply download all files in the component folder in this repo `(foobar components)` or from the site itself. I will include all of the links to the component used here so you can read their functions more in depth and check out their respective authors:



**Essential Components:**

_Spider Monkey Panel_ - https://github.com/marc2k3/foo_spider_monkey_panel/releases/tag/1.6.2.25.11.15

_Columns UI_ - https://www.foobar2000.org/components/view/foo_ui_columns

_JSplitter_ - https://foobar2000.club/forum/viewtopic.php?t=6378

_Waveform Minibar_ - https://www.foobar2000.org/components/view/foo_wave_minibar_mod

_spectrum analyzer_ - https://www.foobar2000.org/components/view/foo_vis_spectrum_analyzer

_Openlyrics_ - https://www.foobar2000.org/components/view/foo_openlyrics

**Biography and Library Tree Package Packages (Essential):**

- **DO NOT UNZIP THESE PACKAGES**
- Just download them and leave them as is.

_biography_ - https://github.com/Wil-B/Biography/releases/tag/v1.4.2

_library tree_ - https://github.com/Wil-B/Library-Tree/releases/tag/v2.4.0


**Last FM Components:**

_Scrobble_ - https://www.foobar2000.org/components/view/foo_scrobble

_playcount stats_- https://www.foobar2000.org/components/view/foo_playcount

_Playcount sync_ - https://marc2k3.github.io/component/lastfm-playcount-sync/

**Extra Components:**

_Albumlistpanel_ - https://www.foobar2000.org/components/view/foo_uie_albumlist

_sox,dsp resampler_- https://www.foobar2000.org/components/view/foo_dsp_resampler

After downloading, your folder should look something like this, ready to install:


<img width="350" height="463" alt="image" src="https://github.com/user-attachments/assets/53879262-453b-4026-89f9-129e4bb6ed7c" />

- Ignore Biography and Library Tree for now.
  
### Installing Components 
- Once you have your components downloaded and stored, you are ready to actually install them. 
- Simply go to File > Prefrences > Components > Install
- Select all components in your folder and your components should be updated like this:

<img width="738" height="408" alt="image" src="https://github.com/user-attachments/assets/09508f15-50da-416c-b4f4-315181db127e" />

- Hit apply and foobar will restart itself to apply the changes.

### Preparing Biography and Library tree packages
- Since we installed the Columns UI component, upon start up we should see these choices.
- **Choose Columns UI**

<img width="587" height="257" alt="image" src="https://github.com/user-attachments/assets/947d3afe-6b9e-49d5-ad64-2ccd8b9a0386" />

- Now that we are in Columns UI, we can continue installing Biography and Library Tree. 
- These use the Spider Monkey Panel (SMP) environment we just installed so lets try creating one.

- Click on 'Live Layout Editing' and right click a panel to add a SMP like so:

<img width="816" height="717" alt="image" src="https://github.com/user-attachments/assets/0914bb0b-df4b-4687-b756-5ae131644dcd" />


- Here is what it should look like:
- Note: I accidently downloaded the older verision of SMP 1.6.1. You should use 1.6.2 which is what this theme uses. If you downloaded from the link I provided or from the repo, you should have 1.6.2 installed.

<img width="840" height="417" alt="image" src="https://github.com/user-attachments/assets/e1d1351e-2854-4e87-96bf-1d5aee04d80e" />


- Now that we have a SMP we can finish installing Biography and Library Tree.
- First, deselect 'Live Layout Editing'

<img width="188" height="87" alt="image" src="https://github.com/user-attachments/assets/37e74379-277a-4e7c-a879-d0d0d6b1d6c8" />

- Now, Right click the SMP and hit 'Configure panel..'
  
<img width="374" height="225" alt="image" src="https://github.com/user-attachments/assets/144642e4-c5ff-4ce0-8f3f-010b6175f64b" />

- Now go to the 'Script' tab and click 'Packages'. You should now be in the menu to import both Biography and Library Tree

<img width="496" height="391" alt="image" src="https://github.com/user-attachments/assets/33181016-2870-4962-bfa8-f21f6b3f0590" />

<img width="165" height="102" alt="image" src="https://github.com/user-attachments/assets/37afedd1-79ea-4abd-baef-648a1f0b0e40" />

- It should now look something like this:

<img width="502" height="473" alt="image" src="https://github.com/user-attachments/assets/6c5e6e6c-09f9-4a77-b7ed-f36bf6f54767" />

- Now just to make sure they are working properly, we should test them before we import the theme.
- Make sure your media library is pointing to your music folder. File > Preferences > Media Library > Add Folder and Apply

- Follow the same steps above! Live Layout Editing and right click to add another SMP
- Deselect Live Layout Editing and right-click to configure panel.
- Add Biography or Library Tree!

<img width="731" height="821" alt="image" src="https://github.com/user-attachments/assets/dbb41ead-b2f2-4943-abbd-7bf78621876c" />

<img width="684" height="711" alt="image" src="https://github.com/user-attachments/assets/7a53352d-a6f6-457c-ba17-3d3d5a38cd6d" />

- Biography and Library installed successfully:


<img width="728" height="398" alt="image" src="https://github.com/user-attachments/assets/96d2e0c2-e955-48c5-a6f0-58ebdd3d5ebe" />

- We can finally import the theme

### Importing Theme 
File > Preferences > Columns UI > Import Configuration...

<img width="521" height="454" alt="image" src="https://github.com/user-attachments/assets/ec687dc5-c46c-45f2-a479-50c801a723ef" />

<img width="434" height="423" alt="image" src="https://github.com/user-attachments/assets/1ac083d5-9a80-43b8-9827-cf44edaf4b2d" />

- Select OK

- You may notice a pop up of 'Slideshow no valid images found!' Nothing is wrong, this is just my Dynamic image panel script telling you that there are no images specified yet. Close it and we can go back to it once we finish setting the theme up. 

<img width="731" height="384" alt="image" src="https://github.com/user-attachments/assets/0793a001-9948-4305-a145-b47ce827c468" />

- Looks odd but we just need to tweak it a bit.
- If you are still on light mode make sure to change it to dark
- File > Preferences > Display > Columns UI > Colors and Fonts > Dark mode

<img width="446" height="272" alt="image" src="https://github.com/user-attachments/assets/5c61300d-b979-4d8d-98c5-86de501411b0" />

<img width="718" height="408" alt="image" src="https://github.com/user-attachments/assets/0aa6aa35-365e-4193-9113-814355316f0b" />

- Now the colors are accurate! But where are the rest of the panels? 
Some of the panels are collasped and just need to be adjusted to your screen. Since my theme was made on a 24in monitor, my small laptop doesnt have enough screen for that so we need to adjust with the dividers. 
- File > Preferences > Display > Columns UI > Layout > Misc to adjust the divider widths. (set it to a value other than 0 to adjust)
- Pull this divider out:

<img width="690" height="462" alt="image" src="https://github.com/user-attachments/assets/7fc8c476-a12a-4430-8268-ae30a4e218b5" />

- Also adjust this by pulling down:

<img width="475" height="307" alt="image" src="https://github.com/user-attachments/assets/bde23dba-069e-4bd9-9c06-d2ed9b5f76cc" />


- Our playback controls are also hiding so pull that up
  
<img width="708" height="195" alt="image" src="https://github.com/user-attachments/assets/3eeed5c7-99ee-450e-b717-8e53319fda37" />

- The top panel as well to reveal the visualizer:
 
<img width="719" height="123" alt="image" src="https://github.com/user-attachments/assets/913162e0-b022-4f15-9afb-f7742f9ae3c9" />

- After adjusting:
  
<img width="732" height="717" alt="image" src="https://github.com/user-attachments/assets/add7fdec-2efc-439f-97ef-344a4b98ee40" />

- However, we should remove the top toolbar as it is mostly redundant as the theme already includes the file menu, playback buttons, device selector and playback order.
- Remember, the foobar icon is a SMP script. It does the same functions as the toolbar above

<img width="344" height="227" alt="image" src="https://github.com/user-attachments/assets/b6066f3d-fb87-4845-b227-50a459cf6dfc" />

- Go to preferences > Display > Columns UI > Main Window and uncheck 'Show Toolbars'

<img width="688" height="548" alt="image" src="https://github.com/user-attachments/assets/d30bba23-d5b6-4cd3-8472-04398f0d0e3e" />

- Much cleaner!

<img width="736" height="390" alt="image" src="https://github.com/user-attachments/assets/401d2f22-a3d8-49f6-9adc-0dbbdfd31d9a" />

## Icons, Waveform, Control Panel Fixes

<img width="736" height="161" alt="image" src="https://github.com/user-attachments/assets/5d0806d9-3669-4d03-8e94-9bc320412d71" />

- There are still issues with the waveform bar and icons why?
- Just like the panels, we need to just adjust the waveform bar. And for the icons, we simply just need to download a few fonts.
- I have already included all of the fonts in the repo `(foofonts)` folder. Simply download the raw files and place them into your folder.
- Here are the links for the fonts as well:
  
**Webdings 1-3:**
- https://github.com/justrajdeep/fonts/blob/master/Webdings.ttf
- https://github.com/justrajdeep/fonts/blob/master/Wingdings%202.ttf
- https://github.com/justrajdeep/fonts/blob/master/Wingdings%203.ttf

**Guifx V2:**
- https://www.dafont.com/guifx-v2-transports.font

**Fontawesome:**
- https://github.com/beakerbrowser/beakerbrowser.com/blob/master/fonts/fontawesome-webfont.ttf

**Microsoft Segoe Fluent Icons font:**
- https://learn.microsoft.com/en-us/windows/apps/design/downloads/#fonts

- Once you downloaded them, here is how it should look like:
<img width="328" height="265" alt="image" src="https://github.com/user-attachments/assets/e5e2f22b-2d98-409f-bd18-9e72fbf3eb32" />

- No need to unzip
- To install them, simply double click on the zip file and open the TTF

<img width="714" height="523" alt="image" src="https://github.com/user-attachments/assets/9fa3dd5d-71b6-4f2e-b76e-5dbc8e55c12b" />

- Then Click 'Install'

<img width="708" height="395" alt="image" src="https://github.com/user-attachments/assets/b60c6004-dad6-40cb-81a6-ee67d4695f88" />

- Then proceed to open the TTF files and install the rest of the files like so!

<img width="648" height="507" alt="image" src="https://github.com/user-attachments/assets/146d44c5-7ec2-4e7b-b57e-d8978f3a08a1" />


- After you install the fonts, **Restart Foobar**
- After restart:

<img width="332" height="76" alt="image" src="https://github.com/user-attachments/assets/dcf724b3-fb47-4809-8824-ee4a38dd009d" />

- Our icons are now working!

#### Waveform Minibar
Now for the final step is to adjust the waveform mini bar. 
- Ctrl + P or Top left, foobar icon, File > preferences > display > columns ui > layout 
- Scroll down to 'Waveform Minibar' and click 'Show Caption' Hit OK
- Another faster way is to just use live editing like so and you can right click the wavebar and show the caption that way:
  

<img width="609" height="239" alt="image" src="https://github.com/user-attachments/assets/841446d4-8a06-4088-be24-f83047b3fe5d" />

Right click on the waveform bar

<img width="298" height="246" alt="image" src="https://github.com/user-attachments/assets/926bf50c-57ae-4ebe-afe2-ea72d1cc364f" />

-  Make sure to disable live editing when you are finished

- You can now adjust it like a normal window to fit your screen

<img width="739" height="62" alt="image" src="https://github.com/user-attachments/assets/cd0cb82a-e76e-4217-837d-756b15aadd36" />

- Once you are done, right click and uncheck show caption
<img width="398" height="135" alt="image" src="https://github.com/user-attachments/assets/ff0539db-74b4-489c-80bf-3e5e41a580a7" />

<img width="726" height="115" alt="image" src="https://github.com/user-attachments/assets/7238b332-20e4-411f-b1d2-e15c00404882" />

- Looks better!
- But there still a weird outline, why? 
- We just need to uncheck a box in preferences. Simply right click the waveform bar and click 'configure'
- Check 'Transparent background (require Columns UI)' and Uncheck 'Draw window border'

<img width="739" height="571" alt="image" src="https://github.com/user-attachments/assets/b0d00b1c-25bf-42ca-b119-60acd4e47aaa" />

### Final Touches
One last step!
- Once you have everything set and adjusted to your liking, you can remove the grey borders so you dont accidently move them again.
- File > Prefrences > Layout > Misc
- Set the divider width px to 0. 
- If you ever need to adjust again, just set it to a value other than 0

- If you did all the steps correctly this is how the theme should look like!

14in Laptop:

<img width="1920" height="1030" alt="image" src="https://github.com/user-attachments/assets/00fab575-ade9-478d-9c66-97dc90af03f2" />

24in Monitor:

<img width="2558" height="1381" alt="image" src="https://github.com/user-attachments/assets/d3fd5329-4722-4314-8ffc-facd8212a9b5" />

## Tips and How To Use Theme

### Cover main view Usage

<img width="639" height="1181" alt="image" src="https://github.com/user-attachments/assets/3d6519c5-5c64-45ac-9d0f-49f6234c5435" />

Components and scripts used here are Biography, Spectrum Analyzer, Openlyrics, Internet Radio and JS Smooth Browser 
- I am just showing you how to navigate or use the basic features. Experiment yourself or check out the main documention from the author themselves.
#### Usage for Biography
Link for additional documentation and author for this script: https://theqwertiest.github.io/foo_spider_monkey_panel/docs/script_showcase/single_panel_scripts/#biography-wilb

- For Biography panel, you can click the title to display more info
<img width="366" height="133" alt="image" src="https://github.com/user-attachments/assets/0dd4b638-94a1-4cce-86f0-255e9595a757" />

- Clicking on the album cover will also reveal additional information about the artist
<img width="651" height="492" alt="image" src="https://github.com/user-attachments/assets/225244ae-08aa-46c4-8a6a-2e41311f4edc" />

- If you don't want the album art background you can change it by right clicking the panel > options > display > theme
<img width="590" height="328" alt="image" src="https://github.com/user-attachments/assets/d43e6e9d-0142-4387-a971-28b30ca6dd16" />

## Open lyrics
- Right click the lyrics panel to search for lyrics or manually
- Some songs have timestamps which is perferable as the lyrics will automatically be in sync with the song. 
<img width="357" height="254" alt="image" src="https://github.com/user-attachments/assets/ff3f12ae-59d1-4552-b9ba-bf4765883a3e" />

<img width="1812" height="592" alt="image" src="https://github.com/user-attachments/assets/d1299692-3a92-42a6-9d23-21af76d3e094" />

- However sometimes songs will have no lyrics (instrumentals only) so the lyrics panel is redundant.
- To provide a solution, simply switch to the Cover View w/o lyrics for those cases!

<img width="342" height="120" alt="image" src="https://github.com/user-attachments/assets/11d476d1-2fd0-4a3c-b23c-9f8540cf050f" />

- If the lyrics panels is too small, you can always adjust or use the right panel under 'Misc' for a longer panel for lyrics.


<img width="965" height="1192" alt="image" src="https://github.com/user-attachments/assets/29eb8cd4-549a-4b33-8e25-df900892219d" />


#### Album Viewer
https://theqwertiest.github.io/foo_spider_monkey_panel/docs/script_showcase/single_panel_scripts/#js-smooth-browser

This panel uses JS Smooth Browser 
- Mainly used for a nice view of your album covers
- Uses Jsplitter environment, not SMP
- However, it is included in the sample scripts in SMP 1.6.1
- It is best to use SMP 1.6.2 which this theme uses.
  
<img width="644" height="1194" alt="image" src="https://github.com/user-attachments/assets/5cb29065-3e58-4ed0-8fd0-d71f30db3184" />

#### Internet Radio

<img width="640" height="1154" alt="image" src="https://github.com/user-attachments/assets/eed858b8-c945-4410-ad15-58c64c985f25" />

### Right-Side Panel
- This panel uses Library Tree, Item Properties, Open Lyrics, and Dynamic Image Panel(mine)

#### Library Tree
- Search
<img width="286" height="354" alt="image" src="https://github.com/user-attachments/assets/5e1a192c-8755-44fd-8b1f-7d6fb05b5121" />

https://theqwertiest.github.io/foo_spider_monkey_panel/docs/script_showcase/single_panel_scripts/#library-tree
- Please click link for more in depth documentation.
- I use this to search to mainly search for artists
- You can also use this to add songs/albums to a playlist by right clicking on a specific artist. 


<img width="314" height="110" alt="image" src="https://github.com/user-attachments/assets/33b83b8a-9a12-4f76-8816-378d8e3d2c27" />


<img width="1443" height="702" alt="image" src="https://github.com/user-attachments/assets/fdf977a3-d677-46e2-9681-c6cd66e2fef5" />

### Item Properties 
- Info
- Simply display track metadata of current song or selected song.

<img width="299" height="1048" alt="image" src="https://github.com/user-attachments/assets/76887d3e-4dec-4fa9-aa34-9adecada0154" />

### Misc.
- Open lyrics panel

### Dynamic Image Panel (main)


<img width="66" height="96" alt="image" src="https://github.com/user-attachments/assets/4c304d51-a9b1-4027-868f-0046674c3e58" />

- My own SMP script, an image slideshow visualizer with extensive customization options.
- Right-click the panel and click 'Configure panel..'
- Specifiy image paths
- Use portrait style images for the best results

<img width="756" height="70" alt="image" src="https://github.com/user-attachments/assets/83eaf317-fa5b-45d5-b1f2-f7c3b5b04da0" />

<img width="1011" height="731" alt="image" src="https://github.com/user-attachments/assets/bf0b7af4-6586-4b3e-9c36-015117ee4721" />

- The first image is set to 'single_zoom' which means it'll only show the first image and zoom at its current specified speed.
- If you want the script to rotate through all you images, set it to 'slide_show'

![Animation1-ezgif com-optimize](https://github.com/user-attachments/assets/e764434a-cb26-49bd-b9e2-1ab850feb9d8)

- To remove the tint or change the color adjust these values:

<img width="541" height="40" alt="image" src="https://github.com/user-attachments/assets/53181876-a8a3-4b06-ab36-5773c7b79c3e" />

- Play around with these options to change the zoom direction
- You can change it to where it'll pan across the image instead of just zooming into the center like so:


<img width="536" height="40" alt="image" src="https://github.com/user-attachments/assets/ff524f44-9f71-4d52-9e76-ff79a72827f1" />

- Can also adjust how long you want an image to persist, just increase/decrease the ms. 

<img width="433" height="26" alt="image" src="https://github.com/user-attachments/assets/0fca3132-bb80-4980-a7c3-57b437d40e08" />

- Fade speed refers to how fast you want the transition to happen to the next image.
- Lower value = slower transition fade

<img width="453" height="25" alt="image" src="https://github.com/user-attachments/assets/2f7f83cb-6282-4ef6-8bd2-aa989891b421" />

- If you just want to have a single image only, you can choose a static or single_zoom mode for that image
- Static will not move.
- Single_zoom will move around using your settings on that image. This will offer a more dynamic mode. 
<img width="1020" height="407" alt="image" src="https://github.com/user-attachments/assets/77345497-d0f5-4956-8d69-913e5380cac5" />


## Left Panel
### Playlist Cover Tab Manager
- Also a script by me.
- Essentially replaces playlist tabs and functions like a spotify-like playlist manager.
- You can do all of the essentials like Save, Load, Delete, Rename, Move, Add and Duplicate playlists.
- Simply right click on a playlist to display all of the options.
- Extensive customization options are also available.
- A github for more details is provided: https://github.com/xaIex/Playlist-Tab-Cover-Manager


<img width="156" height="1151" alt="image" src="https://github.com/user-attachments/assets/2df19b4e-57a6-4413-8202-8d83ad6039be" />

### File Menu
<img width="51" height="61" alt="image" src="https://github.com/user-attachments/assets/7ef4e8e4-ae1b-4be0-b2f0-01dd60d72318" />

https://theqwertiest.github.io/foo_spider_monkey_panel/docs/script_showcase/single_panel_scripts/#main-menu-button
- SMP script that replaces the toolbar

## Main Center Panel
### JS Smooth Playlist, Adding songs to a playlist easily
https://theqwertiest.github.io/foo_spider_monkey_panel/docs/script_showcase/single_panel_scripts/#js-smooth-playlist
- Uses JSplitter environment like JS Smooth Browser. 
- Using the main playlist viewer, JS Smooth Playlist, simply drag and drop to a specified playlist 


<img width="1449" height="710" alt="image" src="https://github.com/user-attachments/assets/8379b887-d593-4e8f-b693-35383d1edcf8" />

- Click the title of the album or the indivdual song to add it to your specified playlist 

### Searching within the playlist
- From the top left, search what artist, song, album you are looking for in that playlist

<img width="216" height="105" alt="image" src="https://github.com/user-attachments/assets/eee9f6e1-8add-42c3-a9cf-59802b73a8ce" />

### Spectrum Analyzer

<img width="1443" height="140" alt="image" src="https://github.com/user-attachments/assets/d261092f-3975-444c-90d8-14382e07fb4b" />

- Curve Peak Line will reflect album art cover
- Right-click > Configure to customize further if needed

## Last FM Profile 
- If you downloaded all of my components you should have this option to sync foobar with last.fm for scrobbling


<img width="659" height="608" alt="image" src="https://github.com/user-attachments/assets/b9fe9911-034a-4acb-818d-7f73f645a58f" />

File > Prefrences > Tools > Last.fm Playcount.Sync

- Make a last.fm account and authorise it.
- You then should be able to click the hearts in the Fluent Control Panel (Credit to u/eurekagliese)


## Editing Theme/Adding your own panels or scripts

- Previously I showed you that you can use the `live layout editing` feature through File > Layout > live editing **OR** File > Preferences > Display > Columns UI > Layout
- I like doing it the second way as it gives me more control and an overview of the layout.
- For example, lets say we want to change some of the panels on the right side of the theme.
- Here is how the layout is correlated to the panels:
- Each entry is nested into the `Tab Stack` which allows us to have mutliple panels in one.
- `Vertical Splitter` Allow for panels to be placed stacked on top of each other.
- `Output Device`, `Playback Order` and SMP for example, are nested in the `Vertical Splitter` which is nested within `Tab Stack`
- Note: Depending on your OS, the naming convention may be different but still the same.
- `Vertical Splitter` = `Column`
- `Horizontonal Splitter` = `Row`

<img width="284" height="350" alt="image" src="https://github.com/user-attachments/assets/b7c7754c-9bb2-44e2-8a51-b94c71c7ceaa" />

<img width="1251" height="672" alt="image" src="https://github.com/user-attachments/assets/c19290dd-913b-4e12-812c-ccee6aaeac97" />

- If you want to add another panel, simply right click on `Tab Stack` and add your panel or splitter like so:

<img width="697" height="357" alt="image" src="https://github.com/user-attachments/assets/cca2a0dc-b4ac-40ee-b0fc-6bf2333df20c" />

<img width="937" height="680" alt="image" src="https://github.com/user-attachments/assets/857f1e88-5afb-47d6-bdea-0d8910eee934" />

- If you want to remove it, simply right click and remove panel

<img width="282" height="123" alt="image" src="https://github.com/user-attachments/assets/425d1bf7-693a-442f-b0d7-8317fd970334" />


- Lets say we want to change the lyrics panel to another panel
- First, remove panel

<img width="276" height="163" alt="image" src="https://github.com/user-attachments/assets/bbbb3302-8d62-4bfd-a99e-f3f5555ff6d8" />

- Go to its parent, `Vertical Splitter` and click right click

<img width="797" height="403" alt="image" src="https://github.com/user-attachments/assets/5a45f887-ef8e-4b9d-bf88-1fafc3ab0d52" />

- You can move around the panel with `Move Up` or `Move Down`

<img width="371" height="171" alt="image" src="https://github.com/user-attachments/assets/2a4408e1-4e64-43f3-bb27-c969d1da9ece" />

- Successfully added!

<img width="328" height="1245" alt="image" src="https://github.com/user-attachments/assets/6ff373ff-b79e-44d2-9e43-34dfd27c05ec" />

- You can now create or editing your own theme to your liking~

## Hotkeys/Shortcuts
- You can further customize your keyboard shortcuts here:

<img width="859" height="672" alt="image" src="https://github.com/user-attachments/assets/1f0e65f5-f2fa-4b91-b42a-d566e81beb0a" />



