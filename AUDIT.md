## Settings
- Slow 3G
- Google Chrome

**Original code loading speeds:**
![Original](https://d.pr/i/JPnHzN+ "Original")

### CSS
- Concatenating and minifying decreased css loading time by 0.73 seconds
- Async stylesheet loading first meaningfull paint decreased by 2 seconds

**No async stylesheets**
![No async stylesheets](https://d.pr/i/MJHlPp+ "No async stylesheets")

**Async stylesheets**
![Async stylesheets](https://d.pr/i/qyDE6n+ "Async stylesheets")   

### Fonts
- Replaced local fonts by CDN decreased font loading time by 8.44 seconds 

**After**  
![After CDN](https://d.pr/i/UvPLBw+ "After CDN")

### JavaScript
- Using a CDN hosted jQuery decreased jQuery loading time by 2.46 seconds.
- Concatenating and minifying JS decreased JS loading time from approximately 15 seconds to approximately 8 seconds

### Images
- Saving the images in a lower quality and resizing them increased the loading speed by approximately 9 seconds.
- Adding smaller images for devices that won't need big images saved

### Compression
- Added GZIP decreased 3.42 seconds of the total loading time.

**GZIP Disabled**
![Without GZIP](https://d.pr/i/YPAG0T+ "Without GZIP")

**GZIP Enabled**
![With GZIP](https://d.pr/i/auSotc+ "With GZIP")
