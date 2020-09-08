# Links
## Writing Links
### Links are created using the < a > element. Users can click on anything between the opening < a > tag and the closing < /a > tag. You specify which page you want to link to using the href attribute.
![a comands](https://user-images.githubusercontent.com/70091044/92458940-bb878800-f1ce-11ea-9cb7-bb17ab1e55b4.PNG)
## Email Links
### (mailto:): To create a link that starts up the user's email program and addresses an email to a specified email address, you use the < a > element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
![link email](https://user-images.githubusercontent.com/70091044/92459815-d1e21380-f1cf-11ea-8308-8773c917ac83.PNG)
## Opening Links in a New Window
### target: If you want a link to open in a new window, you can use the target attribute on the opening < a> tag. The value of this attribute should be *_blank*.
## Linking to a Specific Part of the Same Page
### At the top of a long page you might want to add a list of contents that links to the corresponding sections lower down. Or you might want to add a link from part way down the page back to the top of it to save users from having to scroll back to the top.
### To link to an element that uses an id attribute you use the < a > element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to. In this example, < a href="#top" > links to the < h1> element at the top of the page whose id attribute has a value of top.
![link in same page](https://user-images.githubusercontent.com/70091044/92461272-c1329d00-f1d1-11ea-9585-90c77edae3e5.PNG)
## Linking to a Specific Part of Another Page
### If you want to link to a specific part of a different page (whether on your own site or a different website) you can use a similar technique. As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page.
### For example, to link to the bottom of the homepage of the website that accompanies this book, you would write:
### < a href="http:/www.htmlandcssbookcom/#bottom">
