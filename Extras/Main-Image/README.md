# How to apply.
<ul></li><p><b><< Fast step to apply the config. >></b></p></li></ul>
<p>Add the files <code>ogx_main-image.css</code> and <code>ogx_root-personal.css</code> into the <code>chrome/components</code> folder.</p></br>

<p><i>PD: The file <code>ogx_root-personal.css</code> will set the default values of the theme, if you changed some rule in the file you will need to change again in this new file. The wallpaper will be the named <b>>>wallpaper1.png<<</b> in <code>chrome</code> >> <code>images</code> >> <code>newtab</code>, if you want to change it you will need to replace your new image with that name.</br>You will need to edit the line 42 to set the correct number to align the image if you have active the bookmark toolbar or the menu-bar.</i></p>

<ol><p><b><< Manual steps to apply the config. >></b></p>
  
  <li>Edit the line <code>19</code> into the <code>ogx_root-personal.css</code> file with the code: <code>--wallpaper-size: auto auto ;</code>.</li>
  <li>Edit the line <code>20</code> into the <code>ogx_root-personal.css</code> file with the code: <code>--brightness-wallpaper: brightness(51%);</code>.</li>
  <li> Edit the line <code>43</code> into the <code>ogx_root-personal.css</code> file, uncomment it and write the right number, 
  there is a description on the right side of the rule, That's all. 💙</li>
</ol>

<p><i>PD: Make sure you have active a compatible theme, with some image themes the selected tab will display a black line using this configuration.</i></p>

![imagen](https://user-images.githubusercontent.com/22057609/186757301-ac031f8c-999d-4835-a321-bd1cd93b2980.png)
