Whisper Embed Documentation
===========================

Whisper embeds allow you to embed Whispers on your own website.

![ScreenShot](http://i.imgur.com/48no4FD.png)

### Using Embeds

Go to the [Developer Center](http://developer.whisper.sh/#/embed) to create an embed.

First, paste in the URL of the Whisper you want to embed into Whisper URL.

Second, select the size. Using `auto` is recommended as it allows the embed to be responsive and work on mobile. The other sizes are fixed widths.

Third, select the format. See [types of embeds](#Types of Embeds) to determine which is best for you.

To use the embeds, simply copy the HTML embed code to your website. If using the JavaScript or JavaScript IFrame embeds, you only need to include `<script src='http://cdn-web.whisper.sh/embed/v1' async></script>` once per page.

### Types of Embeds

There are 3 types of Whisper embeds: JavaScript, JavaScript IFrame, and IFrame.

**1) JavaScript Embed**

The JavaScript embed is the fastest, and should be used if possible. It loads the HTML into a div with JavaScript.

**2) JavaScript IFrame Embed**

This version still uses JavaScript, but creates an IFrame for the embed. Use this version if the JavaScript Embed is conflicting with your website in some way.

**3) IFrame Embed**

This version is just an IFrame. Since IFrames are slower, only use this if the other embed types don't work.
