<svelte:head>
  <title>Post-Growth Collective</title>

  
  <meta name="description" content="Help figure out what this thing is!">
  
  <!-- Facebook Meta Tags -->
  <meta property="og:url" content="https://sambutler.us/community-energy-vision/">
  <meta property="og:type" content="website">
  <meta property="og:title" content="Community Energy Vision">
  <meta property="og:description" content="Help figure out what this thing is!">
  <meta property="og:image" content="https://solar.lowtechmagazine.com/dithers/azuri-technologies.png">
  
  <!-- Twitter Meta Tags -->
  <meta name="twitter:card" content="summary_large_image">
  <meta property="twitter:domain" content="sambutler.us">
  <meta property="twitter:url" content="https://sambutler.us/community-energy-vision/">
  <meta property="og:title" content="Post-Growth Collective">
  <meta property="og:description" content="Help figure out what this thing is!">
  <meta name="twitter:image" content="https://solar.lowtechmagazine.com/dithers/azuri-technologies.png">
</svelte:head>

<main>
<h1>Post-Growth Collective</h1>
<p>A collective of people, groups, and communities, interested in making new worlds real.</p>
<p>Want to help figure out what this thing is, or stay updated?</p>

<form>
    <label>Name, or what you'd like to be called</label>
    <input>
    <!-- <input placeholder="Ursula Le Guin, Shevek, X Æ A-12 Musk"> -->

    <label>Email* (the only required item)</label>
    <input>

    <label>Phone number (this helps for connecting!)</label>
    <input>

    <label>What activities would you like to see a post-growth collective focus on?</label>
    <details><summary>Examples</summary>
<p>Real-world transitions in housing, transportation, food, energy, and public services<br><br>

Tools/services which could be building blocks in post-growth worlds<br><br>

Sharing content and raising awareness of postgrowth values<br><br>

Bringing to life stories, music, and cultural initiatives</p></details>
<textarea placeholder=""></textarea>

<!-- <label>What groups, Substacks, clubs, communities are you part of, that could be interested in being part of a post-growth collective? (Seperate by commas)</label>
<textarea placeholder="E.g. Soapbox project, Heated, 

"></textarea> -->

    <label>Are there any groups, initiatives, or communities you're part of, that could be interested in joining a post-growth collective?</label>
    <details><summary>Examples</summary>
        <p>I have a newsletter audience that could be interested<br><br>

The bike advocacy group in my city could be interested<br><br>

My academic club at university would like to join<br><br>

The autonomous zone of Anarres would like to be part of a post-growth collective</p></details>
    <textarea placeholder=""></textarea>     
        <!-- re there any groups or communities that you lead or are part of, that you would like to join the collective?  (e.g. IRL group, Research network, Newsletter community?)</label> -->
<!-- <textarea placeholder="e.g. I have a newsletter subscriber community, and they would probably like to be involved in this.

I lead a bike advocacy group in my city, and people would be onboard.

My peers and I at university have an academic club that would like to join.

We, the 800-person citizenry of Vatican City, would like to join the post-growth collective as a sovereign nation.

"></textarea> -->

    <label>What are your favorite post-growth inspirations?  (Ideas, research papers, sci-fi books, quotes, real-world movements, postgrowth scenarios)</label>
    <details><summary>Examples</summary>
        <p>"Decent living with minimum energy: a global scenario"<br><br>

            "A world where many worlds fit"<br><br>

            The writing and philosophies of Ursula Le Guin<br><br>
            
            Indigenous philosophies on relationality from Turtle Island<br><br>
            
            "Avalon" by Barry Levinson (watched in reverse, is postgrowth in the USA!)<br><br>
            
            Zapatistas in Mexico<br><br>
            
            Research and Degrowth community<br><br>
            
            Twitter postgrowth / degrowth<br><br>
            
            "Tools for Conviviality" by Ivan Illich</p></details>
    <textarea placeholder=""></textarea>

    <label>City</label>
    <input>

    <label>Country</label>
    <input>

    <label>Twitter handle (while it lasts ...)</label>
    <input placeholder="">

    <label>Are you okay with any of these responses being public? (So we can put ourselves on a map or something!)</label>
    <div style="padding: 1em;">
    <div class="checkbox">
    <span>My name can be public</span>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My email can be public</label>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My activities response can be public</label>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My groups/communities response can be public</label>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My inspirations response can be public</label>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My city can be public</label>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My country can be public</label>
    <input type="checkbox">
    </div>
    <div class="checkbox">
    <label>My Twitter handle can be public</label>
    <input type="checkbox">
    </div>

        </div>

    <em style="text-align: center; display: block;">"The means is the end.  But what if there is no end?  Then there's only the means."</em>
    <br>
    <button type="submit">Submit</button>
</form>
<br>
<footer>
<p>Social media preview image from <a href="https://solar.lowtechmagazine.com/2018/01/how-much-energy-do-we-need.html">Low tech magazine.</a>  
<br>
Language inspired by Donna Haraway.</p>
<a href="/terms">Terms of access</a> | <a href="/privacy">Privacy policy</a>
</footer>
</main>
<style>
    form > label, input {
        display: block;
    }

    form {
            /* margin: auto; */
            width: 500px;
            max-width: 100%;
            margin-top: 1em;
            padding: 1em;
        }

    textarea {
        max-width: 100%;
        width: 460px;
        height: 100px;
    }

    input {
        width: 300px;
    }
    
    input, textarea {
        margin-bottom: 1em;
    }

    div.checkbox > * {
        display: inline-block;
        width: min-content;
        white-space: nowrap;
    }

    button[type="submit"] {
        margin: auto;
        display: block;
    }

    details > p {
        font-style: italic;
    }

    main {
        padding: 0em 1em;
    }

</style>