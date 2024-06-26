---
title: About
description: We've built an amazing team of developers, marketers, designers and sales people.
image: https://source.unsplash.com/BcoGknSqlDc/2000x1322?a=.png
---

<section class="hero" style="background-image: url({% include relative-src.html src=page.image %})">
	<div class="inner-hero text-container">
		<div class="hero-text-container">
			<h1 class="editable">Our Story</h1>
			<p class="subtext editable">
Navedia Young has expertise in additional needs through her experience in education as a head of year, head of subject, special educational needs, and cognition and learning advisory teacher. She has also delivered presentations and workshops to raise awareness of neurodiversity and was awarded funding to develop dyslexia packs, which were distributed to four London-based boroughs. Additionally, she was an assistant researcher on a project focused on identifying challenges and benefits of accessing technology in emergency situations for the neurodiverse community. Navedia has delivered coaching within the community and is highly recommended. Her Social Enterprise business was named social enterprise of the month in 2022, and in 2023 she won the LEAP community award for supporting parents to engage with their children through sensory stories and sensory creativity.</p>
		</div>
	</div>
</section>

<section class="pad">
	<div class="container">
		<p class="editor-link"><a href="cloudcannon:collections/_staff_members" class="btn"><strong>&#9998;</strong> Manage Staff Members</a></p>
		<ul class="staff">
			{% for person in site.staff_members %}
				<li>
					<div class="square-image" style="background-image: url({% include relative-src.html src=person.image_path %})"></div>
					<div class="name"><a target="_blank" href="https://twitter.com/{{ person.twitter_username }}">{{ person.name }}</a></div>
					<div class="position">{{ person.position }}</div>
				</li>
			{% endfor %}
		</ul>
	</div>
</section>
