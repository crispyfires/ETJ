# How to set up coverage for the Bards College Expansion  


Hey guys! Thanks to Discord user @BearMama, I have been given a copy of the kinggath Creation Bards College Expansion! What this means is that for those of you who own it or are interested in it, I'll have pre-generated files and this instruction guide to have official coverage for switching to BCE!  

Now, to be sure, this _does_ mean that you'll have to do some modding stuff, but don't worry- you'll have everything you should need to follow this guide and get the profile set up.  


## Setting up a new profile  

First, we need to set a new profile up in MO2 so we don't mess up the base install of the list. To do this, click on the dropdown menu where it has the profiles now. It should look like this:  


<img width="1845" height="1202" alt="image" src="https://github.com/user-attachments/assets/290776cf-d622-49b1-a7b3-a7aff84efdfc" />  


Select "Manage" and copy whichever profile you use. I generally play on Nevernude Default, so I'll be copying that profile.  


<img width="484" height="364" alt="image" src="https://github.com/user-attachments/assets/84d4bf0b-4402-4b64-bccc-558045b28a64" />  


Next, name the profile. I'm just going to name it "BCE Profile" myself. Hit "Select" with your new profile highlighted and it'll switch you to editing that profile.  


## Adding Bards College Expansion and its patches    

Okay, now, before we remove any mods ALREADY in the list, we're going to add Bard College Expansion to the list. You need to have already downloaded it to your main install after purchasing it.  

We're going to start by making an empty mod folder in the "Vanilla Quest Tweaks" separator. Do this by right-clicking the separator, mousing over "All Mods," then selecting "Create Empty Mod Inside."  


<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/628832d1-2970-4163-bc06-3cca8d7eba97" />  


Name it "Bards College Expansion," then hit save. Enable the mod that it makes, then right-click and select "Open in Explorer."  

Next, open your Steam install that should have the BCE files in the Data folder, then select them and copy/paste them into the mod folder you just created.  


<img width="1875" height="891" alt="image" src="https://github.com/user-attachments/assets/e7d9ba2d-e1e9-4e1c-a0b8-189bfa4f96b2" />  


<img width="1875" height="891" alt="image" src="https://github.com/user-attachments/assets/fbf1dc2d-122c-477d-b1fd-40d53cac97d0" />  


Refresh MO2 and you should see kinggathcreations_bard.esm in the right-hand pane at the bottom of the "ESMs and ESLs" group. Enable it and move it a little further up in the load order. I put it here (Priority 122):   


<img width="530" height="391" alt="image" src="https://github.com/user-attachments/assets/9dd8699a-9ed8-49f1-bf45-19ee17ae8e45" />  


There you go, Bards College Expansion itself is installed. But there's more work to do!  

Now we need to go to [the patch hub website](https://forum.kinggathcreations.com/resources/bards-college-expansion-unofficial-patches.5/) and download the patches. Right-click on the "Vanilla Quest Tweaks" separator like before, but this time we're going to select "Install Mod Inside," then install the .zip file from the patch hub. Don't forget to enable the mesh replacer option in the FOMOD since this requires manual selection and the list uses JS Instruments. Enable the mod, then sort all of the patches appropriately in the right pane. I usually select the patches, right-click, and hit "Send To," then "Top," as this should put them right under the mods they patch for. 


<img width="438" height="106" alt="image" src="https://github.com/user-attachments/assets/b51cb387-aab6-4a07-aa84-11894b56bc6b" />  


These 4 plugins need to be manually sorted. In order as they appear in the screenshot above, they go in "New Lands and Quests," "General Clutter Updates," "3DNPC," then "LOTD Updates and TCC."  

Next, we're going to [download an NPC replacer](https://forum.kinggathcreations.com/resources/verses-and-voices-a-bce-replacer-pack.11/) for the pack. This time, we're going to download the 1.1 main file from the Google Drive that comes up:


<img width="1770" height="1147" alt="image" src="https://github.com/user-attachments/assets/83834c3d-ee87-4f21-a0e8-88c81a0804ed" />  


Then we're going to download the HDT-SMP Patch and Peras New Armoury patches, they're the last 2 files in the patch hub:  


<img width="1770" height="1147" alt="image" src="https://github.com/user-attachments/assets/5e82a89f-642f-42ef-89f3-06ffe14822a8" />  


Install these files the same way we installed the patches, only this time, they'll go in the "NPC Visual Overhauls" separator. Install and enable them, then sort the new plugins into the "NPC Replacers" group in the right pane as well. They can just go at the bottom of the group, like so:  


<img width="457" height="318" alt="image" src="https://github.com/user-attachments/assets/78e6a7fd-9d25-434b-b8a2-6f63a7d31f7a" />  



## Disabling mods that aren't currently patched for BCE  

Okay, next we need to disable things that don't play well with BCE. First, everything related to Skyrim's Got Talent has to go:  


<img width="1845" height="1202" alt="image" src="https://github.com/user-attachments/assets/d22af89a-b82c-415c-ac83-35abde3bd1d0" />  

<img width="1845" height="1202" alt="image" src="https://github.com/user-attachments/assets/bef81d3f-ad06-4d0e-baf3-8f6dfe91448b" />  

<img width="1845" height="1202" alt="image" src="https://github.com/user-attachments/assets/7c30ab3b-3abe-4211-92b5-c12a1113b4ad" />  

<img width="1845" height="1202" alt="image" src="https://github.com/user-attachments/assets/d1e19c80-8125-4a42-a15a-9f65911a2431" />  


Basically anything with Skyrim's Got Talent, "X Follower Reacts to Your Music," or SGT in the title has to be disabled. That mod is incompatible with BCE and will likely never work with it.  

Additionally, disable the following outputs for now:  


<img width="833" height="474" alt="image" src="https://github.com/user-attachments/assets/af432b64-df25-45ca-856f-22394413d019" />  


We will be making new outputs in new folders in the next step.  

Unfortunately, though patches are currenty planned for these interiors, we also must disable JK's The Winking Skeever and JK's The Bards College along with any associated patches. If the patch hub updates to have patches for these interiors, this portion will be removed. 


<img width="1845" height="1202" alt="image" src="https://github.com/user-attachments/assets/3509393a-c98b-4c5a-9540-215efb0b1e52" />  


There are a LOT of patches for these mods in the list. Make sure you're disabling all of them that show up in the right pane. Failure to do so may cause your game to CTD. Make sure _all_ plugins that show "missing master" warnings are disabled.    

Now that everything else is disabled, we need to have the updated custom patches; these should already be in the correct folder, but if they're not, go to the #bards-college-expansion-support channel in the Discord and download the custom patches from the pinned comment with them. These go in your ElderTeej - xEdit Outputs folder, and they should be rearranged into the "Outputs and Custom Patches" group after loading into MO2. For now, they can be kind of loosely arranged, but the ElderTeej Master Patch BCE Version should be at the top of the group. A final order after running Synthesis is below.



## Setting up folders for your new outputs and running them  

Just like when creating a new folder for the BCE mod, we also now need to make new folders for the outputs, so you don't overwrite the base list's info. Please note that you should find pre-generated BCE Synthesis and BCE PG Patcher folders in the "LEAVE DISABLED" separator at the bottom of the left pane, along with a BCE Master Patch folder. Enable these and place them your Outputs separator. Much like before, right-click, only this time do it on each mod one-by-one, and as before, mouse over "All Mods," but this time your option should say "Create Empty Mod Above". You need to do this for the TexGen and DynDOLOD Output folders; it should look like this when you finish:  


<img width="365" height="287" alt="image" src="https://github.com/user-attachments/assets/42c803b6-7849-4360-a079-7cb35fddfd52" />  
 


If you are going to use my pre-generated outputs, [go to the Nexus page](https://www.nexusmods.com/skyrimspecialedition/mods/154704) and download the BCE - TexGen Output and BCE - DynDOLOD Output files under Miscellaneous. Install these with the same name as the folders you made earlier, let them replace when MO2 asks, then make sure that the PG Patcher ESPs and DynDOLOD ESPs are at the bottom of where they can load. Your right panel should look like below:  


At the bottom of the "ESMs and ESLs" group:   
<img width="523" height="304" alt="image" src="https://github.com/user-attachments/assets/b5e01319-418a-41c6-82e9-67da5d4238a2" />  



At the bottom of the "Outputs and Custom Patches" group:  
<img width="427" height="324" alt="image" src="https://github.com/user-attachments/assets/f2fd9672-5939-4aab-ae64-9bcef3321cde" />  


Congrats! You should be able to start up ElderTeej with the Bards College Expansion officially working!  


## Running TexGen and DynDOLOD if you DO need to  

Now, some of you may be doing some rule 11 stuff that adds world edits/new worlds. If that's the case, _do not use my pre-made PG Patcher ESPs or the TexGen and DynDOLOD files I generated,_ because you need to run all the outputs yourself. I won't be throwing xLODGen instructions in here, as I feel that if you're adding worldspace changes into a list this size, that's a step you ought to be able to do already.  

However, if you added _anything else_ PG Patcher needs to accomodate, you will need to run TexGen and DynDOLOD yourself as well. First things first, let's run TexGen. Just like any other apps in MO2, select it in the dropdown menu and hit play. Once it comes up, the menu will launch to generate everything. By default it should output to Tools\DynDOLOD\TexGen_Output and when it finishes, you can create a .zip file you'll need to install. Just hit CTRL+M in the main MO2 window and it will let you select the file to install; as with my pre-made outputs, I would name this the same name you gave the new BCE TexGen Output folder and just let it overwrite.  


My TexGen settings are:  
<img width="527" height="764" alt="image" src="https://github.com/user-attachments/assets/0a160ba3-6320-4c43-b2dd-8b16f8da81ca" />  



Once you've generated the TexGen outputs and installed them, it's time to start DynDOLOD up. Once the UI comes up, you'll want to choose what level of quality you want the outputs to be made at. I recommend Medium settings, then you need to make sure the rest of your choices match mine here:  


<img width="888" height="597" alt="image" src="https://github.com/user-attachments/assets/85ab8a1e-3ae8-4589-bbcc-abe790d3d3c9" />  

Crucially, these fields must match EXACTLY:  
<img width="895" height="46" alt="image" src="https://github.com/user-attachments/assets/a926afc3-a66a-43e4-a011-18c5a7014393" />  


Just like with TexGen, CTRL+M to install these outputs, name them the same as the output folder you created earlier, replace, and enable. Sort the plugins in the order I showed above, then you should be good to go!  
