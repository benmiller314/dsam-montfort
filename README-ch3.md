# Playing with programming... and poetry

In this repository, we're going to continue practicing with GitHub – and now also try out the exercises in [chapter 3, "Modifying a Program," from _Exploratory Programming for the Arts and Humanities_ (2nd edition)](https://mitpress.ublish.com/ebook/epah2e-preview/12629/31) by Nick Montfort.

The goal is to learn some programming fundamentals by messing around with some existing scripts. In this case, we'll be specifically looking at some JavaScript poetry generators embedded within HTML pages. You do not need any prior programming experience! You do, however, need a plain-text editor like [Pulsar](https://pulsar-edit.dev/) or [VS Code](https://code.visualstudio.com/).

# Instructions


## Part 1: Find the code

_NB: The numbered instructions below are only slightly modified from Montfort's, which begin on page 33. My variations will appear in bold._

1. Go to **[https://codeberg.org/nickmontfort/memslam/src/branch/main/the_house_of_dust.html](https://codeberg.org/nickmontfort/memslam/src/branch/main/the_house_of_dust.html)**, where Montfort has recreated a 1967 script by Alison Knowles and James Tenney. Use the download button <span class="btn-octicon" data-tooltip-content="Download file" aria-label="Download file"><svg viewBox="0 0 16 16" class="svg octicon-download" aria-hidden="true" width="16" height="16"><path d="M2.75 14A1.75 1.75 0 0 1 1 12.25v-2.5a.75.75 0 0 1 1.5 0v2.5c0 .138.112.25.25.25h10.5a.25.25 0 0 0 .25-.25v-2.5a.75.75 0 0 1 1.5 0v2.5A1.75 1.75 0 0 1 13.25 14Z"></path><path d="M7.25 7.689V2a.75.75 0 0 1 1.5 0v5.689l1.97-1.969a.749.749 0 1 1 1.06 1.06l-3.25 3.25a.75.75 0 0 1-1.06 0L4.22 6.78a.749.749 0 1 1 1.06-1.06z"></path></svg></span> to save the file to your own computer. <figure><img src="img/download-button.png"></figure>

2. Double-click the html file you downloaded in step 1 and it will open in your browser. Watch for a minute to see how the page works.

3. Now open the file in your text editor. You can do this in a few ways: use File > Open; right-click the file and use Open With...; or drag and drop it into an open text editor window.

4. Use File > Save As to make a copy of the file with a new name like _'house-of-%name%.html'_, replacing '%name%' with your first name. There should be no spaces, no apostrophes, and no percent symbols in the filename.**
    * If your operating system is configured to conceal file extensions from you, this is a great time to turn that off so you can see the `.html` that indicates a Web page and, later on, the `.py` that indicates a Python file, not to mention the extensions that indicate text files and different types of image files. All the GNU/Linux distributions I know about show the extensions by default. If you use Mac OS X, the option to show file extensions can be reached by clicking on the desktop to activate the Finder and then selecting Finder > Preferences > Advanced. On Windows, open the File Explorer and look at the View tab.

Find the file in your computer's system (e.g. Finder on Mac, or Explorer on Windows), and double-click to open it. If it has the `.html` extension, it should appear in your default web browser, but instead of having an `http://` address, it'll be under something like `file:///`. Why? Because you're not transferring data across the internet, so you don't need to use a HyperText Transfer Protocol.


## Part 2: Change the code

We're now up to Montfort's [section 3.3](https://mitpress.ublish.com/ebook/epah2e-preview/12629/34).

1. Head back into your text editor and look for the words in all caps: 'SAND', 'DUST', etc.

2. Change them and save the file. You don't need your lists to be as long as the ones there, but make sure you've got at least a few variations that you'll recognize as your own.

3. Go back to your browser and refresh the page.

<div class="alert alert-info">
<p>Pause to discuss. What happens?</p>

<p>What lets you know what you can change and keep the program intact, and what would break the program if you changed it?</p>
</div>

<ol start="4"><li>If you're happy with this changed version of your generator, go ahead and <strong>commit the change</strong>, using a meaningful commit message (beyond "updated file"). And if you're not sure how to do that, please ask. :¬)</li></ol>


## Part 3: Explore the possibilities

We're now up to Montfort's [Free Project 3-1](https://mitpress.ublish.com/ebook/epah2e-preview/12629/36), copied below. By "the six listed previously," Montfort means one of these, and I actually do recommend sticking to these for now (you can always try something else at home):

* [nickm.com/poems/perverbs.html](https://nickm.com/poems/perverbs.html)
* [nickm.com/poems/upstart.html](https://nickm.com/poems/upstart.html)
* [nickm.com/poems/lede.html](nickm.com/poems/lede.html)
* [nickm.com/memslam/love_letters.html](https://nickm.com/memslam/love_letters.html)
* [nickm.com/memslam/stochastic_texts.html](https://nickm.com/memslam/stochastic_texts.html)
* [nickm.com/memslam/a_house_of_dust.html](https://nickm.com/memslam/a_house_of_dust.html) (but we've already done this one)

<blockquote>
<strong>Do this project three (3) times, using two (2) different Web pages as your starting point.</strong> Start with a particular combinatory textual toy in HTML with JavaScript—a simple one, although your selection doesn’t have to be one of the six listed previously. Modify the program so that its output is somehow substantially different. It could contradict the original system, for instance, or the tone could be completely different, or the system could produce unrelated output. Beyond replacing some text with other text, see if you can make changes to the way the system functions. For instance, if your system generates sentences, can you change the syntax of the sentences it outputs—adding adjectives or moving parts of speech around—rather than just changing the lexicon? For this exercise, restrict your work to the JavaScript code (in the <code>&lt;script&gt;</code> element) rather than modifying the HTML. Modifying HTML can be fun and rewarding too, but our focus is on programming, not on structured documents or their appearance.
</blockquote>

<div class="alert alert-success">
<p>See how many changes you can make while time allows – and have fun with it! Each time you reach a moment of satisfaction, go ahead and commit the change, using a meaningful commit message (i.e. beyond just "updated file").</p>

<p>NB: Make a new file for each new <em>source page</em>, giving it a unique name... but then <strong>keep the same filename for your revisions within that file</strong>, so your changes will show up as diffs.</p>

<p>If you find you've broken something, you can Edit > Undo within the text editor; or you can go back and copy from an old commit; or you can go all the way back and copy from the original source again. This is a safe space for experimentation and exploration. :¬)</p>
</div>

EXT: Feeling like you've gleaned all you can glean from hacking this code? Check out [https://www.lillianyvonnebertram.com/](https://www.lillianyvonnebertram.com/) and explore the Projects and Poems tabs to see how one professional does it. Remember that you can see the source code for any of the dynamic projects!


## Part 4: Share it back

After the break, we'll talk more about the experience, and hopefully get to see some poem-generators in action. To make your examples more visible, please **push your changes** to the cloud.

From there, we'll be able to view them [online](network).
