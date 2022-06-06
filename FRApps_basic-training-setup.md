
# Steps to install Docsify for FRApps-basic-Training

   1. Create a new empty repository: github.com/suzeeparker/FRApps-basic-training

   2. Either create a new local repository or use an existing one
      - if new, run git init
      - if old, make sure that .git exists and commits are up to date
        - I'll be using a clone of Rick's repo as of last Thursday

   3. Enter the new local repository and open it
      ```
      cd C:/Repos/FRApps_/basic-training
      code . 
      ```
      
   4. Set the login URL for your GitHub account
      ```
      git remote remove origin
      git remote add origin "gitbub_sue:suzeeparker/FRApps-basic-training"
      ```
   
   5. Commit all new files and push them up to the new empty repository 
      ``` 
      git commit 
      git 
      ``` 
   
   6. Create chapter folders
      ```
      mkdir chapter1
      mkdir chapter2
      ```

   7. Move the 5 "App" folders into a `Chapter1` folder.
      This is similar to our normal 'client1' folder. Rename the 5 folders
      to indicate that they are belong to chapter 1.
      ```
      mv 1_BasicBasicBlocks          1c1_BasicBlocks
      mv 2_BasicBasicLargeBlocks     2c1_BasicLargeBlocks
      mv 3_BasicBasicWithFixedHeader 3c1_BasicWithFixedHeader
      mv 4_BasicBasicWithImage       4c1_BasicWithImage
      mv 5_BasicBasicWithFooter      5c1_BasicWithFooter
      ```

   8. Copy a `docs` folder into the local repository
   
   9. View the docs 
      - Select the file `./docs/index.html`
      - Open it with `Live Server`
      
   
   