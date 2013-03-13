---
title: My opinion on CSS preprocessors
layout: post
preview: true
comments: false
---
<section>
<p><strong>Disclaimer!</strong> Yes, another blog post about CSS preprocessors. No, I won't try to convince you to use one. I just want to share my thoughts on the topic.</p>
<p>A couple of days ago, the famous french front-end developer <a href="https://twitter.com/iamvdo">Vincent De Oliveira</a> has written a blog post called <a href="http://blog.iamvdo.me/post/45259636008/pourquoi-je-nutilise-pas-les-preprocesseurs-css">Why I don't use CSS preprocessors</a> ("Pourquoi je n'utilise pas les préprocesseurs CSS"). If you can read French, or stand Google Translate, then I highly recommand you this article, full of good points and interesting opinions.</p>
<p>Please don't consider this post as an answer to Vincent's one. I just wanted to <strong>share my opinion on the topic</strong>, not to open a flame war. Especially since I like this guy. :)</p>
</section>
<section id="tldr">
<h2>Tl;dr <a href="#tldr">#</a></h2>
<p>There is no point debating about whether preprocessors are good or evil: they are good. If you think they are evil, it's either because you're afraid of them, or because you suck with them. The question isn't even which one to choose: they all do pretty much the same even if Sass is slightly more robust than others. The main topic is: <strong>should or shouldn't we use one</strong>?</p>
<p>There are cases where you don't want to use a preprocessor (whatever the language). The main case is when your team involves some beginners or inexperienced developers: if they are not very comfortable with the language, it will be even worse with a preprocessor.</p>
</section>
<section id="maintainability">
<h2>Maintainability <a href="#maintainability">#</a></h2>
<p>I think the key word here is <strong>maintainability</strong>. You will never ever reach the same level of maintainability without a CSS preprocessor. Ever.</p>
<p class="pull-quote--right">I think the key word here is maintainability.</p>
<p>However, you might not need that level of maintainability. As <a href="https://twitter.com/kaelig">Kaelig</a> says in his article <a href="http://blog.kaelig.fr/post/24877648508/preprocesseurs-css-renoncer-par-choix-ou-par">CSS preprocessors: renounce by choice or ignorance?</a> ("Préprocesseurs CSS, renoncer par choix ou par ignorance?"): if you work on small projects or one-shot websites, you may not need a preprocessor. Let's be realistic for a minute: you won't update the site everyday, if at all. If you ever happen to do so, you can dig into the code without having to use of a preprocessor.</p> 
</section>
<section>
<h2>They give CSS what CSS needs</h2>
<p>Vincent says preprocessors don't add anything to the default language. In a sense, yes. Sass isn't magic. CoffeeScript isn't magic. Markdown isn't magic. In the end, they render CSS, JS and HTML.</p>
<p>But CSS preprocessors give CSS what CSS lacks of. CSS lacks of variables, above all. CSS possible lacks of simple nesting for pseudo-classes. CSS might lack of functions and mixins. Preprocessors give developers all this stuff. <strong>Without altering performances</strong>.</p>
<p><strong>Yes, we can do sites with these features.</strong> It's just nice to have them. Saying otherwise would be a big fat like. But of course we can still make sites without preprocessors.</p>
<p><strong>I don't need a preprocessor</strong>. I say it: I don't. I'm not working on 10000-lines stylesheets. I'm not working on multiple templates websites. I'm not working on complex CSS architectures. I could do every single project I do without Sass.</p>
<p>But <strong>Sass looks better than CSS to me</strong> (at least in most cases). I like being able to use variables. I like being able to use mixins and functions. I like being able to use Compass. I like all of this stuff, even if I don't necessarily need it. It feels more normal to me.</p>
</section>
<section id="">
<h2>Quality code <a href="#">#</a></h2>
<p>Let's make things clear right now: <strong>preprocessors don't output bad code, bad developers do</strong>. CSS preprocessors -whatever the one you (don't) use- do not generate top-heavy, unwiedly, unnecessarily complicated code. This is a lie bad developers will tell you to explain the quality of their code.</p>
<p class="pull-quote--right">Preprocessors don't output bad code, bad developers do.</p>
<p>If the final stylesheet is less maintainable or heavier, or more complicated than the vanilla CSS version you had before using a preprocessor, <a href="http://pastebin.com/Jy9PqFTy">it's because you messed up</a>. Not because of Sass.</p>
<p>Vincent does an interesting comparison with PHP (HyperText Preprocessor): you can output shitty code with PHP too. Is it because of PHP? Definitely not. It's because you've messed up.</p>
</section>
<section id="">
<h2>Speed <a href="#">#</a></h2>
<p>Some people say preprocessors don't make you write CSS faster. Indeed, you won't become Iron Man as soon as you run Sass, definitely not. Even if in the end, you write code slightly faster; simply by the fact you don't have to write vendor prefixes for example.</p>
<p>You don't save much time while coding. You save time when it comes to maintain and update your stylesheets. It's a no brainer.</p>
</section>
<section>
<h2>Learning curve <a href="#">#</a></h2>
<blockquote><p>Preprocessors make CSS more complex. [...] I said more "complex" not more "complicated". You can think preprocessor's syntax is simple, it is still more complex than the default one.</p></blockquote>
<p>Vincent is definitely right on this one. Preprocessors sometimes make the syntax more complex by adding new features; not necessarily more complicated, simply more complex (no pun intended).</p>
<p>One of the biggest concerns when talking about CSS preprocessors (and preprocessors in general) is the learning curve. Most try to stay as close as possible to the CSS syntax but they involve new features with their own syntax, which need to be learnt. Yes, <strong>it needs some time to wrap one's head around a preprocessor</strong>, especially if it involves a very different syntax from the original language (Sass, CoffeeScript).</p>
<p>If you happen to be a beginner or work with inexperienced developers, you probably shouldn't use preprocessors. Someone who's not very comfortable with a language could do <a href="http://pastebin.com/Jy9PqFTy">pretty bad things</a> with a preprocessor. Adapt your tools to your team.</p>
</section>
<section id="final-words">
<h2>Final words <a href="#final-words">#</a></h2>
</section>