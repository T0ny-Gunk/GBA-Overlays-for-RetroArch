# GBA-Overlays-for-RetroArch
I decided to create authentic looking bezeless overlays after seeing many on the internet.

I got inspired by some of the default overlays in RetroArch and wanted to implement one which would show different overlays even if you change orientation from horizontal to vertical and vice versa.

I have used PhotoPea and RetroPad Editor to make these. I'm still a beginner so my initial work will look shoddy so apologies :), I'm still learning.

I would like to give credits to Reddit user u/Cris_250299 whose post [here](https://www.reddit.com/r/EmulationOnAndroid/comments/mg9o7e/universal_snessfc_skin_for_retroarch/) gave me the idea about seamlessly switching orientations and to Reddit user u/Lyceux whose post [here](https://www.reddit.com/r/RetroArch/comments/1d9adim/wasnt_a_fan_of_the_existing_overlays_so_i_made_my/) helped me used the assets that they designed for this project. Shout out to both of them! 

[Video of the overlay working in both orientations](https://www.reddit.com/r/RetroArch/comments/1lhkk1i/tried_making_my_own_custom_bezeless_overlay_for/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

##Installation:

1. Download the folder as a zip file by clicking the Code section.

2. Extract the folder inside the zip file in a suitable location in your phone.

3. Go to your playlists -> open the playlist where your game is located -> select the game of your choice -> run game

4. Then click on the retroarch logo 
![looks like this](https://github.com/user-attachments/assets/8692b9a1-2046-443a-9104-04bd299ebcbe) and then go to On-Screen Overlay.

5. Select Overlay Preset and then navigate to the folder that you have extracted and select the 'gba portrait landscape overlay.cfg' file.

6. Now go back to your quick menu by clicking the top left arrow and change your Overlay Opacity value to 1.00.

7. Make sure the following options are configured as mentioned below:

   i) Show Overlay Behind Menu: Off

   ii) Hide Overlay in Menu: On

   iii) Hide Overlay when Controller is Connected: Off

   iv) Show Inputs on Overlay: Touched

   v) Show Mouse Cursor with Overlay: On

   vi) Auto-Rotate Overlay: On

9. Now, toggle off Auto-Scale Overlay. You should be able to see various values. Make sure the values are as follows:

   i) (Landscape) Overlay Scale: 1.000

   ii) (Landscape) Overlay Aspect Adjustment: 0.000

   iii) (Landscape) Overlay Horizontal Separation: 0.000

   iv) (Landscape) Overlay Vertical Separation: 0.000

   v) (Landscape) Overlay X Offset: 0.000

   vi) (Landscape) Overlay Y Offset: 0.000

   vii) (Portrait) Overlay Scale: 1.000

   viii) (Portrait) Overlay Aspect Adjustment: 0.000

   ix) (Portrait) Overlay Horizontal Separation: 0.000

   x) (Portrait) Overlay Vertical Separation: 0.000

   xi) (Portrait) Overlay X Offset: 0.000

   xi) (Portrait) Overlay Y Offset: -0.025

10. To save your changes, now exit from On-Screen Overlay section and then scroll to Overrides.

11. Now, there are many options so it's upto you:

    i) If you want this overlay only for a particular game, then click on Save Game Overrides.

    ii) If you want this overlay only for all content in the same content directory, then click on Save Content Directory Overrides.

    iii) If you want this overlay for all content loaded with the core, then click on Save Core Overrides.

12. After choosing your Overrides options, now click the Setting icon (looks like a cogwheel). Don't quit your game and then do this or else this will be global and will reflect on all cores!

13. Go to Video -> Scaling.

14. Configure the values as mentioned below:

    i) Integer Scaling: Off

    ii) Integer Scale Axis: Y+X

    iii) Integer Scale Scaling: Smart

    iv) Aspect Ratio: Config

    v) Config Aspect Ratio: 1.33 (usually will be automatically filled)

    vi) Viewport Anchor Bias X: 0.50

    vii) Viewport Anchor Bias Y: 0.50

    viii) Viewport Anchor Bias X (Portrait Orientation): 0.50

    ix) Viewport Anchor Bias Y (Portrait Orientation): 0.00

    x) Bilinear Filtering: Off

    xi) Crop Overscan (Restart Required): On

15. Go back to Overrides in the Quick Menu (if you can't find it, then select the 3 bullet points with lines -> Select your playlist -> Select your game -> Overrides.

16. Repeat the same choice that you've made in step 11.

17. Now you can go back to your game and check out the overlay! All buttons should be working and the overlay look will automatically change based on your phone's orientation.

That's it! Congratulations, now you can use this overlay and it'll automatically change according to the orientation that your phone is in. Hope you enjoy this!

This is fully working but I believe I can add more buttons in the future so feedback will be appreciated!

Anyone who wants to improve on this can go ahead! Please fork the repo so that I can see your progress 😁


