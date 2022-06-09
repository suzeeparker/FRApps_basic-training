
<meta property="og:title"       content="Docsify Setup Videos">
<meta property="og:description" content="This page contains videos that describe how to use setup and use Docsify.">
<meta property="og:url"         content="https://formr.net/">
<meta property="og:image"       content="https://suzeeparker.github.io/FRDocs_dev01-suzee/assets/formr-icon.png">

# Docsify Docs in Github

<!-- --------------------------------------------------------------------- -->

## 1. Create a new remote repository:
   - Go to to your account on www.github.com    
  
   ```
   github.com/suzeeparker/FRApps-basic-training 
   ```
   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID01b" class="video-toggle_btn">Show Video</a><br>
       <video id="VID01" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_1. Create Repo.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->

## 2. Open a local repository in VSCode

   1. Either create a new local repository or use an existing one
      - if new, run git init
      - if old, make sure that .git exists and commits are up to date
        - I'll be using a clone of Rick's repo as of last Thursday   

   2. Enter the new local repository and open it
      ```
      cd C:/Repos/FRApps_/basic-training
      code . 
      ```  
   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID02b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID02" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_2. Open local in VSCode.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->

## 3. Set and push local to remote repository 

   1. Set the login URL for your GitHub account
      ```
      git remote remove origin
      git remote add origin "github_sue:suzeeparker/FRApps_basic-training"
       ```

   2. Push local files up to the new empty repository 
      ``` 
      git push --set-upstream origin master
      ```
   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID03b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID03" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_3. Set remote origin.mp4" type="video/mp4">
       </video>
     </div>
   
<!-- --------------------------------------------------------------------- -->

## 4. View populated remote repository      
   
   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID04b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID04" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_4. View remote.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->
<!--
## 5. Commit new changes

   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID05b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID05" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_5. Commit changes.mp4" type="video/mp4">
       </video>
     </div>
-->
<!-- --------------------------------------------------------------------- -->

## 5. Create chapter folders

   1. In Terminal for File Explorer  
      ```
      mkdir chapter1
      mkdir chapter2
      ```
   2. Move the 5 "App" folders into a `Chapter1` folder.  
      This is similar to our normal 'client1' folder. Rename the 5 folders
      to indicate that they are belong to chapter 1.  
      ```
      mv 1_BasicBasicBlocks          1c1_BasicBlocks
      mv 2_BasicBasicLargeBlocks     2c1_BasicLargeBlocks
      mv 3_BasicBasicWithFixedHeader 3c1_BasicWithFixedHeader
      mv 4_BasicBasicWithImage       4c1_BasicWithImage
      mv 5_BasicBasicWithFooter      5c1_BasicWithFooter
      ```
   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID06b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID06" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_6. Create chapter folders.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->

## 6. Add ./docs folder
   1. Copy a `docs` folder into the local repository
   
   2. View the docs 
      - Select the file `./docs/index.html`
      - Open it with `Live Server`

   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID07b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID07" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_7. Add docs folder.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->

## 7. Commit staged changes      
   
   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID08b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID08" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo01.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->

## 8. Enable docs in remote repository   

   <div style="margin: 10px 0px -5px 0px;">
           <a id="VID09b" class="video-toggle_btn" onclick="videos_toggle(event)">Show Video</a><br>
       <video id="VID09" width="872" controls>
         <source  src="/FRApps_basic-training/FRDocs/Setup-Docsify/videos/sp20606-09-101_FRApps1-ExpVideo02_9. Enable docs site.mp4" type="video/mp4">
       </video>
     </div>

<!-- --------------------------------------------------------------------- -->

<script>
    
            videos_hide()
            videos_addOnClick()

//--------  ------------------------------------------------------------------ 

  function  videos_hide() {

       var  mVideos = document.querySelectorAll( "video[ID^=VID]" );
       for (var  i = 0; i < mVideos.length; i++) {
       var  pVideo = mVideos[i]
       var  aID    = pVideo.attributes['id'].value
       var  pLink  = document.querySelector( '#' + aID + 'b' )
        if (pLink) {
//          console.log( aID, pLink.innerText )
            pVideo.style.display = 'none'
            pLink.innerText = "Show Video"
            }  }
         }
//--------  ------------------------------------------------------------------ 

  function  videos_addOnClick() {

        var mVideos = document.querySelectorAll( "video[ID^=VID]" );
       for (var  i = 0; i < mVideos.length; i++) {
       var  pVideo = mVideos[i]
       var  aID    = pVideo.attributes['id'].value
       var  pLink  = document.querySelector( '#' + aID + 'b' )
        if (pLink) {
            console.log( aID, "Adding onClick event listener" )
            pLink.addEventListener("click", videos_toggle )
            }  }
         }  
//--------  ------------------------------------------------------------------ 

  function  videos_toggle( pEvent ) { 
  
       var  pLink  = pEvent.currentTarget
       var  aID    = pEvent.currentTarget.attributes['id'].value.replace( /b/, '' )
       var  pVideo =  document.querySelector( '#' + aID )
       var  bShow  =  pLink.innerText.match( /^show/i )
//          alert( `${aID}: ${bShow ? "Showing" : "Hiding"} video.\n Changing link text from ${pLink.innerText} to ${bShow ? "Hide" : "Show"} Video.` )
            pVideo.style.display = bShow ? 'block' : 'none'
            pLink.innerText = (bShow ? "Hide" : "Show") + " Video"
         }
//--------  ------------------------------------------------------------------ 

//  windows.videos_toggle = videos_toggle  // windows is not defined 
//          alert( videos_toggle )
//          alert( global )

</script>

<div style="height: 2000px"/>
