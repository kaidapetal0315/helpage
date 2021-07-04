
## 👷‍♂️**How to Personalize Helpage?**
1. [Fork]() the Repository.
2. Clone the Repository to your Local Environment.
3. Search for `<WELCOME MESSAGE>` in `/index.html` and Update Your Name there.
<br>
<br>

### Adding New Icon to the Page
1.  In Order to add a new icon to Helpage, you'll need the following beforehand:
    - `LINK` to the Website you want to add.
    - An `IMAGE/SVG` for the Logo of the Concerned Website (or Any Relevant Reference Picture you want to have).
2. Upload the `IMAGE/SVG`, into `assets/` folder with an Appropriate Name *( let's call it ICON_1 for example )* and Extension *( **.png**, **.jpg**, **.jpeg**, **.svg** are some of the extension that'll work fine )*.
    - Your File should have a relative path similar to `assets/ICON_1.png` *(For Example)*.
3. Once you've gathered everything listed above and added the Logo
    - Open `Index.html` and find `<ADD ICON HERE>`. 
    - You'll have to decide where exactly you want to add your new icon in the page & find exactly **that particular** `<ADD ICON HERE>` comment.
4. Copy and Paste the following lines of code ***on the line JUST ABOVE*** the `<ADD ICON HERE>` Comment.

    ```
    <!-- <ADD ICON HERE> -->

    <!-- <INSERT NAME> -->

      <div class="col-sm-4 col-4 col-lg-2 col-md-3">
        <div class="icons dark-elem">
          <a href=" <ADD LINK HERE> " target="_blank">
            <img src="assets/<NAME OF IMAGE/SVG>" alt="<ALT TEXT>" height="100px">
          </a>
        </div>
      </div>
    ```
    Update the folllowing Values accordingly.
    - `<INSERT NAME>` : Name of Website You've Linked.
    - `<ADD LINK HERE>` : `LINK` to the Website.
    - `<NAME OF IMAGE/SVG>` : Name of The Logo Image/SVG file added to `assets/` folder ( For this Example -  `ICON_1.png` )
    - `<ALT TEXT>` : Name of Website You've Linked.

  #### `👌 You've Successfully Added a New Icon!! `
<br>
<br>


### Deleting An Existing Icon On The Page
1. Find the `<ADD ICON HERE>` comments **Above and Below** the Icon you want to remove.
2. Delete everything in between the two comments.
3. Remove Any **ONE** of the `<ADD ICON HERE>` comments. *( Optional but Recommended )*
#### `👍 You've Successfully Removed an Icon. `
<br>
<br>

### Adding New Bookmark

1. Find `<ADD BOOKMARK HERE>` in `Index.html`.
2. Copy and Paste the following lines of code ***on the line JUST ABOVE*** the `<ADD BOOKMARK HERE>` comment.

    ```
    <!-- <ADD BOOKMARK HERE> -->
    <a href="<ADD BOOKMARK LINK>" class="dropdown-item"><INSERT BOOKMARK NAME></a>
    ```
    Update the following values accordingly:
    - `<ADD BOOKMARK LINK>` : Link to the Bookmarked Website.
    - `<INSERT BOOKMARK NAME>` : Name of the Bookmarked site.
3. Additionally, if you want a Bookmark Divider, Paste the following line at Required place.
    ```
    <div class="dropdown-divider"></div>
    ```
#### `👌 Bookmark Added Successfully `
<br>
<br>

### Removing Existing Bookmarks...
1. Find the `<ADD BOOKMARK HERE>` comment **Above and Below** the Bookmark you want to remove.
2. Delete everything in between the comments.
3. Remove Any **ONE** of the `<ADD BOOKMARK HERE>` comments. *( Optional but Recommended )*
#### `👍 Successfully Removed a Bookmark `