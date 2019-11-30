# bookmarks
customized browser bookmark panel
How to create your own bookmark panel for your browser

by Jeff Macharyas

Let’s say you wanted a collection of bookmarks for a particular subject. You could create a folder of each bookmark in your browser and organize them that way.

Or, you can create your own customized bookmark page in HTML. It’s easy—here’s how I did it.

I wanted to keep a collection of presidential candidates’ campaign sites bookmarked. I selected 12 candidates to keep track of.

I simply created an HTML document using WordPad (PC).

1. Download open source images of each candidate from Wikipedia Commons.
2. Using InDesign (or any similar program, such as Scribus), create a set of pages to place the images.
3. Type in the name of the candidate.
4. Copy your first page (image and text) and relink the image on page 2 to the next candidate. Type that person’s name. Repeat until all candidates’ pages are created (I created 12).
5. Export all pages as individual JPG images.
6. Upload them all to an accessible place online. I placed my in Google Photos.
7. Open the photo in Google Photos and right-click on the image. Select “Copy Image Address.” This will copy a very long URL.
Or: Keep all the images, design files and HTML on your local drive, such as a folder on your Desktop.
8. Paste that entire block of text in the IMG SRC part of the HTML. Be careful to get the whole text and place it between <img src="….."></a>.
9. Go to the candidates’ campaign site and copy that URL from the address bar.
10. Paste the campaign URL between <a href="...">
11. Copy that entire block and paste it below and repeat these steps until all selected sites are complete.
12. Save the HTML document.
13. From your browser, select File>>Open and select the HTML file you created (or double click to open in your default browser). This will open a “web page.” Add it to your bookmark bar or folder.

Now, you have one bookmark, that when opened will display the HTML file you created with images and links.

I tested this on Windows 10 with Chrome, Firefox, Brave, Internet Explorer and Edge.

Additional HTML formatting can be added as you choose (fonts, colors, backgrounds, etc).
