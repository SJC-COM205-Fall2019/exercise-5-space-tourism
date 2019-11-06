<h1>Student Exercise:  Space Tourism – The Grand Tour</h1>
<p>The purpose of this exercise is to work with creating CSS based layouts in Dreamweaver and image sizing techniques in Photoshop.    Please read all instructions before you begin.</p>
<p>Use the mockups, <strong><em>reference_space_tourism_grand_tour.jpg </em></strong>and<strong><em> reference_space_tourism_posters.jpg</em></strong>, as a guide to help you identify different elements on your page.  </p>
<h2>In this exercise, you will:
</h2>
<ul>
<li>Identify html tag structure</li>
<li>Format Text using Dreamweaver </li>
<li>Insert Images</li>
<li>Create and attach a new CSS style sheet</li>
<li>Create and apply CSS styles to a webpage</li>
<li>Use a Google Font</li>
<li>Create a CSS based page layout using the Box Model Math Concepts</li>
<li>Create a navigation bar with CSS</li>
<li>Sizing Images using Photoshop</li>
</ul>
<h2>Instructions – Home Page:</h2>
<ol>
<li>Create a dev branch off master<br>
</li>
<li>Begin processing your images.  In Photoshop open the images from Assets &gt; Poster Images.   Using the Image Size dialog, size the poster images to 175x261.  Save your processed images into the folder <em>images &gt; posters</em>.<br>
</li>
<li>Open <em>reference_space_tourism_grand_tour.jpg</em> and identify the html elements needed to structure your page  (Note the headings, paragraphs, lists and links) <br>
</li>
<li>Create a new HTML file and save it as <em>index.html.<br>
</em></li>
<li>Using the mockup as a guide, begin to layout you page as we did in class.  Draw the container first, and create divs inside the container for the header, nav, content, sidebar and footer.  Look at the CSS references below for class names.</li>
<li>Using the mockup as a guide, copy/paste the text and format using the properties panel.  Refer to the folder <em>Assets &gt; Copy</em> for text.</li>
<li>Create your navigation list.  Enter the following and then format as a bulleted list using the properties panel.  Link to the following: 
	<ul>
	<li>Home – Link to index.html</li>
	<li>Destinations – Link to <a href="https://www.jpl.nasa.gov/visions-of-the-future/">https://www.jpl.nasa.gov/visions-of-the-future/</a></li>
	<li>The Future – Link to <a href="https://www.jpl.nasa.gov/visions-of-the-future/about.php">https://www.jpl.nasa.gov/visions-of-the-future/about.php</a></li>
	<li>Posters – Link to posters.html (you will have to type this manually).</li>
	<li>NASA – Link to https://www.nasa.gov/</li>
	<li>JPL  - Link to https://www.jpl.nasa.gov/</li>
	</ul>
</li>
<li>Import the images a shown in the mockup, making sure to add your alternate text.
<ul>
<li>Header Image Alt = A Once in a Lifetime Getaway – The Grand Tour</li>
<li>Content  Image = Planet Illustration</li>
<li>Visions of the Future Image = Views from Titan</li>
<li>Galactic Travel Destinations = Geysers on Enceladus</li>
</ul>
</li>
<li>Embed the Youtube video:  <a href="https://www.youtube.com/watch?v=Kn54NZZiuEY">https://www.youtube.com/watch?v=Kn54NZZiuEY</a><br>
Sized at 640x360, uncheck show suggested videos.<em><br>
</em></li>
<li>Create a new CSS style sheet named styles.css and attach it index.html<br>
</li>
<li>Use the following Google Fonts for your page:
<ul>
<li>Headings – Anton, 400 </li>
<li>Body Copy – Lato, 400 + 700 weights</li>
</ul>
</li>
<li>Figure out your Box Model Math for your index page with the following information:
<ul>
<li>Container – 1152px </li>
<li>Gutters – 54px</li>
<li>Sidebar – 345px</li>
<li>Content - ???</li>
</ul>
</li>
<li>Style your page elements using the following table:<br />
<table border="1" cellspacing="1" cellpadding="3">
<tr style="background: #eee;">
<td width="180"><p><strong>CSS Selector</strong></p></td>
<td width="454"><p><strong>Properties</strong></p></td>
</tr>
<tr>
<td width="180" valign="top"><p>body</p></td>
<td width="454" valign="top"><ul>
<li>Font   family: Lato + Arial Font Stack</li>
<li>Font   color: # 151419</li>
<li>Font size:   14px with a line height of 20px</li>
<li>Background   Color: # f4e8d2</li>
<li>Margin:   0px</li>
<li>Padding:   0px</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.container</p></td>
<td width="454" valign="top"><ul>
<li>Margin   Top/Bottom: 0</li>
<li>Margin   Left/Right: Auto</li>
<li>Padding:   0</li>
<li>Width:   1152px</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.content</p></td>
<td width="454" valign="top"><ul>
<li>Margin:   0</li>
<li>Padding   Top: 36px</li>
<li>Padding   Right: 27px</li>
<li>Padding   Bottom: 36px</li>
<li>Padding   Left: 54px</li>
<li>Width:   ???</li>
<li>Float:   left</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.content_wide</p></td>
<td width="454" valign="top"><ul>
<li>Margin:   0</li>
<li>Padding   Top/Bottom: 36px</li>
<li>Padding   Right/Left: 54px</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.sidebar</p></td>
<td width="454" valign="top"><ul>
<li>Margin:   0</li>
<li>Padding   Top: 36px</li>
<li>Padding   Right: 54px</li>
<li>Padding   Bottom: 36px</li>
<li>Padding   Left: 27px</li>
<li>Width:   345px</li>
<li>Float:   right</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.footer</p></td>
<td width="454" valign="top"><ul>
<li>Clear:   both</li>
<li>Margin   Top: 0</li>
<li>Margin   Right: 54px</li>
<li>Margin   Bottom: 36px</li>
<li>Margin   Left: 54px</li>
<li>Padding   Top/Bottom: 9px</li>
<li>Padding   Left/Right: 0</li>
<li>Border-top:   2px solid # 2c2232</li>
<li>Font-size:   12px;</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>h2</p></td>
<td width="454" valign="top"><ul>
<li>Font   Family: Anton + Arial Font Stack</li>
<li>Font   Size: 20px</li>
<li>Font   Color: # 09a2aa</li>
<li>Font-weight:   normal</li>
<li>Text-transform:   uppercase</li>
<li>Margin Top:   30px</li>
<li>Margin   Bottom: 12px</li>
<li>Margin   Left/Right: 0</li>
<li>Padding:   0</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.img_border</p></td>
<td width="454" valign="top"><ul>
<li>Border:   2px solid # 2c2232</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.nav</p></td>
<td width="454" valign="top"><ul>
<li>Background:   # e40f18</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.nav ul</p></td>
<td width="454" valign="top"><ul>
<li>Margin:   0</li>
<li>Padding:   0</li>
<li>List-Style:   none</li>
<li>Height:   56px</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.nav ul li</p></td>
<td width="454" valign="top"><ul>
<li>Float:   left</li>
<li>Margin:   0</li>
<li>Padding:   0</li>
<li>Text-align:   center</li>
<li>Width:   192px</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.nav ul li a</p></td>
<td width="454" valign="top"><ul>
<li>Display:   block</li>
<li>Font-size:   22px</li>
<li>Line-height:   56px</li>
<li>Color:   #f4e8d2</li>
<li>Font-weight:   700</li>
<li>Text-Transform:   uppercase</li>
<li>Text-decoration:   none</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.nav ul li a:hover</p></td>
<td width="454" valign="top"><ul>
<li>Background:   # 09a2aa</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.poster_table</p></td>
<td width="454" valign="top"><ul>
<li>Margin   Top/Bottom: 9px</li>
<li>Margin   Right/Left: 0</li>
</ul></td>
</tr>
<tr>
<td width="180" valign="top"><p>.poster_table td</p></td>
<td width="454" valign="top"><ul>
<li>Padding   Top/Bottom: 18px</li>
<li>Padding   Right/Left: 0</li>
<li>Text-align:   center</li>
</ul></td>
</tr>
</table>
</li>
<li>Save your changes</li>
<li> Upload your files to github</li>
</ol>
<br />
<h2>Instructions – Posters Page:</h2>
<ol>
<li>Do a <em>File Save As </em>from the index page and name it posters.html.  Use <em>reference_space_tourism_posters.jpg</em> as a reference.
</li>
<li>Remove the sidebar as we did in class by selecting it with the tag navigator.
</li>
<li>Remove all content form the content div except the heading 2 and enter text from the mockup.
</li>
<li>Select the content div using the tag navigator.  In the properties panel change the class form &lsquo;content&rsquo; to &lsquo;content_wide&rsquo;
</li>
<li>Insert a table like we did in class that has 2 rows and 5 columns.  Make sure to set cell-spacing and cell-padding to zero.
</li>
<li>Add your poster images as shown in the mockup.  Making sure to add your alternate text to each image using the image file name.
</li>
<li>Select the table using the tag navigator at the bottom.  Apply the class poster_table.
</li>
<li>Save your changes
</li>
<li>Upload competed project to github
</li>
</ol>
