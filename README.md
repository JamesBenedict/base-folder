# ids-buildout-base

<em>A work in progress guide to developing a long form article  for the Indiana Daily Student outside of our content managment system.</em>
<p>This template is adapted from <a href="http://specials.idsnews.com/caps/"> Waiting for Help</a> pubished in the Spring of 2015 at the <a href="http://www.idsnews.com">Indiana Daily Student</a>. It is being developed for stories from Bonnie Layton's mutlimedia section of the Words and Pictures course at IU in the Fall of 2015. Please don't hesitate to shoot me an email if you have any question. 

<h2>Stories developed from this template</h2>
<ul>
	<li><a href="http://http://specials.idsnews.com/yaolin/">Friends regret not calling the police, describe a pattern of repeated abuse</a></li>
</ul>

<h2>Rules if you plan on publishing in the IDS</h2>
<p>Follow all commented instructions and call all ids.css or ids.js last in your html. There is no absolute style rulebook, and we're open to changes as long as you have a compelling justification. </p>

<p>Try to keep the digital desk updated on your story throughout your reporting and not just when you're ready to publish. The earlier we know how you're going to tell the story the better it will work online. I'm excited if you want a featured added so just let me know if you have any ideas. We will likely be debugging eight to ten stories at the end of the semester, so we need to already be familiar with your code and its issues before then.</p>

<p>We host everything on github, but if you're not comfortable working with it you can also just give us your code. It can't include any server-side programming like Ruby, Python, PHP, etc. but I don't imagine you would ever need to. 
All project folders must be less than 80MB, so size down all your media to only what's needed for the web. There is a lot of extra javascript in the template's index.html as it shows you every option available. Try to keep as much media in your folder as possible, but if you need to use an external service to host it use an official IDS news account.</p>
<h4>Prefered Services for files</h4>
<ul>
	<li>Youtube</li>
	<li>Soundcloud</li>
	<li>Gryphon (This is our CMS and you can use it to host photos)</li>
</ul> 

<h4>File optimization</h4>
<ul>
	<li>Upload photos to gryphon and then link to the url in your html file</li>
	<li>Save as jpg, with twice the image size you want to display and with low compression</li>
	<li>Remove all unused media</li>
	<li>more to come later</li>
		
</ul>

<h4> Schedule to Publish</h4>
<p>Start editing your code with the digital desk a week before publication. We should already know you want to publish with us before a week though. Think of debugging like copy editing. There are going to be problems, and I’m here to help make your code as clean as possible. The more you comment on your code, the easier it will be to understand.</p>

<ul>
	<li>Day 5</li>
		<ul>
			<li>Tell us what is envolved with your story</li>
			<li>Submit a headline/slug</li>
			<li>List of the types of media in your article and generally where they are going to go</li>
			<li>How close you think you are to a finished website</li>
		</ul>
	<li>Day 4</li>
		<ul>
			<li>Work with us to identify bugs you already know about</li>
			<li>Check the design falls into the ids style guide</li>
			<li>Create specific todo before publication list</li>
		</ul>
	<li>Day 3</li>
		<ul>
			<li>More debugging</li>
			<li>Fix style inconsistencies</li>
			<li>Optimize files and remove unused media</li>
		</ul>
	<li>Day 2</li>
		<ul>
			<li>Final day of debugging</li>
			<li>Cut features that still aren’t working</li>
			<li>Push final version to server</li>
		</ul>
	<li>Day 1 (night of production)</li>
		<ul>
			<li>Update body copy / captions after they are checked by copy editors</li>
			<li>Check for issues with server</li>
			<li>Allow SNWorks to look over code</li>
			<li>Prepare for social media</li>
		</ul>
	<li>Day 0 (the article is live)</li>
		<li> So far every build out I’ve done had issues appear only once it went live. Normally, they aren’t very complicated (e.g. the wrong resolution of a photo was uploaded, it doesn’t scale down well on iPhone 4, etc.) but you should be able to make changes that morning</li>
</ul>



<h2>Working Notes</h2>
<p>This is still early on and things are probably going to move around a lot quickly.  Expect the first template with a layout grid and basic css by Oct. 17 and another template with working media examples by the end of the following week. The structure should be finalized by the end of October. Then I'm going to work on improving functionality and the overall smoothness throughout the semester. The more feedback I get from you guys, the more bugs will be exposed and the better the final project will be.</p>

<p>There a pretty big range of experience here so I'm going to try and include more notes on my working process and planned features below in case anyone is interested. I tend to ramble so I appologize if it gets long.</p> 

<h4>Types of Supported Media</h4>
<ul>
	<li>Photo</li>
	<li>Video</li>
	<li>Gifs</li>
	<li>Audio</li>
	<li>Pulled Quotes / Numbers</li>
	<li>Teaser / related content</li>
	<li>Highcharts.js</li>
	<li>Mapbox or Google Maps</li>
	<li>Live data tables</li>
	<li>slideshow</li>
	<li>storymap.js</li>
	<li>juxtapostion.js</li>
	<li>timeline.js</li>
	<li>soundcite.js</li>
</ul>

<h4>Things I've used so far</h4>
<ul>
	<li><a href="https://www.google.com/fonts">Google Fonts</a></li>
	<li><a href="http://www.getbootstrap.com/getting-started/#download">Bootstrap 3.3.5</a></li>
	<li><a href="http://https://www.fortawesome.github.io/Font-Awesome">Font Awesome</a></li>
	<li><a href="http://www.highcharts.com/download">Highcharts 4.1.9</a></li>
	<li><a href="https://www.knightlab.northwestern.edu/">Knightlab tools</a></li>
	<li><a href="http://www.ezgif.com/video-to-gif">Online Gif Converter</a></li>
	<li><a href="https://www.jsfiddle.net/">jsfiddle</a></li>
</ul>


