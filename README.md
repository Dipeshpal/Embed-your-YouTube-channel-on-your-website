# Embed your YouTube channel on your website-

First of all download "youmax.js" ans "youmax.css" from this [github repository](https://github.com/Dipeshpal/Embed-your-YouTube-channel-on-your-website).

Then create a html file and follow-

1. Add these three lines in head tag of your html page-

     <!-- Youmax CSS and JS -->
        <link href="youmax.css" rel="stylesheet" type="text/css">\
        <script src="https://code.jquery.com/jquery-3.1.1.min.js"></script>
        <script src="youmax.js" type="text/javascript"></script>

2.  Add following lines on body tag of your html-

```

<!---- HTML ----->
<div id="youmax"></div>

<!-----Script------>
<script>
	$('#youmax').youmax({
	apiKey:'AIzaSyAlhAqP5RS7Gxwg_0r_rh9jOv_5WfaJgXw',
	youTubeChannelURL:"https://www.youtube.com/channel/UCGEoRAK92fUk2kY3kSJMR_Q",
	youTubePlaylistURL:"https://www.youtube.com/channel/UCGEoRAK92fUk2kY3kSJMR_Q/playlists",
	youmaxDefaultTab:"UPLOADS",
	youmaxColumns:4,
	showVideoInLightbox:true,
	maxResults:20,
});
</script>
```

3. Now you can customise youTubeChannelURL, youTubePlaylistURL, youmaxColumns and others from scripts.

4. Open your HTML page see the magic.
