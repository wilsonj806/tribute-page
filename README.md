# tribute-page
Github hosting for the FCC Tribute Page project. Will also be patching to version 2.0.0



## Notes ripped directly from the HTML file, will format soon

images to use:
https://media.newyorker.com/photos/59096f12019dfc3494ea1e2b/master/w_1023,c_limit/100524_r19635_p646.jpg (ai wei wei portrait)
http://i.dailymail.co.uk/i/pix/2010/10/12/article-1319515-0B916CF2000005DC-140_964x620.jpg (sunflower seeds)
https://gdb.voanews.com/A32A86AB-8E2B-42E2-9768-2F5D9E85BD3B_cx0_cy1_cw0_w1597_n_r1_s.jpg (good fences make good neighbors)
https://www.juxtapoz.com/media/k2/galleries/63820/JuxtapozAiWeiwei00.jpg (law of the journey)

links to use:
  <a href="https://en.wikipedia.org/wiki/Ai_Weiwei" target="_blank">Wikipedia Page</a>
  <a href="https://www.newyorker.com/magazine/2010/05/24/its-not-beautiful" target="_blank">New Yorker Article</a>
  <a href="https://www.theguardian.com/artanddesign/2018/mar/12/ai-weiwei-on-the-us-australia-refugee-deal-its-exactly-like-slave-trading target=_blank">Guardian Article</a>
  
quotes
“I think my stance and my way of life is my most important art,” he said. “Those other works might be collectible—something you can hang on the wall—but that’s just a conventional perspective. We shouldn’t do things a certain way just because Rembrandt did it that way. If Shakespeare were alive today, he might be writing on Twitter.”
“I tried both ways, but most of the time I want my voice to be heard,” he says. “I think, as artists, to give just a gesture is not enough. The fight takes a real struggle. To give a moral kind of superiority shows a problem, because we have to see that we’re all together. The struggle makes the meaning. I prefer to have a real fight than withdraw from the fight.”

awards
2015

background image?
http://backgroundcheckall.com/wp-content/uploads/2017/12/low-poly-background-white-7.jpg



### Notes:
- Container-fluid adds 30px of gutter width by default
  * it has a weird interaction when adding it to Bootstrap columns
- Page layout is meant to be relatively simple while implementing as much stuff I learned from the basic front end dev lessons as possible
  * means don't go ham with extra features as 1.) the requirements for this project aren't particularly complicated and 2.) feature creep is real and I don't want to spend 3 weeks on this
- The workflow for finishing this project was kind of rough
  * next time don't preemptively add classes
    - or do specific ones like as follows
	  `p.center{}` where only paragraph elements with the class center get the CSS attribute applied to it
- Also use jQuery to add repeated classes/ CSS attributes
- Make the portrait of Ai Wei Wei responsive and define the height of the row?
- The Bootstrap class `.row` adds -15px margin
- Figure out best practice for using Bootstrap to layout rows and columns along with doing margins and such

