![QuarkXPress 2018 logo](http://www.quarkforums.com/resources/git/githeader.jpg)
# GREP Search and Replace
This JavaScript needs to be installed in QuarkXPress 2018. Feel free to modify this script to your own needs.  
**Please see here on how to install: [**Installation Instructions**](#howinstall)**
## What it does
This script finds a string, based on a RegEx pattern, in a given text box and replaced it with the a provided string (which can also be a regex).

### Prerequisites
This script references a sub script called "basic_checks.js", which is provided in "Dependencies".

### Notes
This sample ships with QuarkXPress 2018.  

### Screenshots
The example here searches for names "First name & last name" and replaces it by "Last name, comma, first name". The regular expression needs to be finetuned, as it doesn't handle names with special characters or hyphens yet.  

Before:  
![QuarkXPress document](http://www.quarkforums.com/resources/git/md_images/grep1.png)  
After:     
![CSV file](http://www.quarkforums.com/resources/git/md_images/grep2.png)  

Video:  
[![Video showing GREP in QuarkXPress](http://www.quarkforums.com/resources/git/md_images/grep_movie_preview.jpg)](http://www.youtube.com/watch?v=v8ywPZ8Ud_M)  

### Version History  
May 2018: Initial version  
## <a name="howinstall"></a>How to install
1. On the GitHub page, download the ZIP by clicking on the green button "Clone or download"  
![Step 1](http://www.quarkforums.com/resources/git/install_images/step1.png)
2. In the popout menu click on "Download ZIP"  
![Step 2](http://www.quarkforums.com/resources/git/install_images/step2.png)
3. Save to your Desktop
4. Unzip (so that you get a folder)
5. Copy the resulting folder to the js folder in your documents folder (**see below**)
6. In QuarkXPress open the "JavaScript" palette  
(via "Window" menu)
7. If you do not see a folder with the name of this JavaScript, click on the little "Home" ("House") symbol.  
![Step 7](http://www.quarkforums.com/resources/git/install_images/step7.png)

Step 5: On MacOS copy to|Step 5: On Windows copy to
---|---
~/Documents/Quark/QuarkXPress 2018/js/|Documents\Quark\QuarkXPress 2018\js\
(so into your "Documents" folder)|(so into your "Documents" folder)

**Run the JavaScript by first double clicking the folder; and then double clicking the Script itself (in the JavaScript palette of QuarkXPress).**

## More Information
More information on QuarkXPress and how to use JavaScript in QuarkXPress can be found here:  
<http://www.quark.com/Support/Documentation/QuarkXPress/>
