<h1> Keyword and On-Page SEO Checklist </h1>
<p><b>IMPORTANT: </b>Quality content that brings value to the user will always increase your website search rank and traffic much more than SEO.   </p>
<p>If you havent already, read chapter one from this article about <a href="https://backlinko.com/on-page-seo">On-Page SEO basics</a> before proceeding. This will give you the foundation you need to move forward with the check list.</p>

<p>The checklist reiterates concepts from the article and shows you how to implement them in Wordpress.</p>

<p>This checklist is a living document and will grow with time. It only covers some of the many aspects of On-Page SEO.</p>

<i>*The wordpress related steps on this checklist assume you have yoast as a plugin. By no means do you have to have a wordpress site to follow these steps but on some steps you may have to do some googling to adapt the solution to your crm or software framework</i><br>

<h2> Select a Keyphrase </h2> 
<details>
<summary>Details</summary>
<br>
<h3>What's a Keyword or Keyphrase</h3>
    <p>A <a href="https://yoast.com/difference-between-keyword-and-keyphrase/">keyword</a> is a word that describes the content of your page or post best. It’s the search term that you want to rank for with a certain page. So when people search for that keyword in Google or other search engines, they should find that page on your website.
    </p>
    <p>
    E.g. Your website is about dogs, and you’ve just written a blog post all about puppies. The keyword that describes the content of that post best is probably: “puppy”. -exerpts from yoast.com
    </p>
<h3>Keyphrase Selection</h3>
    <p>
        <b>Keyphrase</b> selection is important. Do your research before selecting a keyphrase. Ideally a keyphrase should follow your companies <a href="https://yoast.com/what-is-a-keyword-strategy/"><b>keyword strategy</b></a> while having great <a href="https://backlinko.com/hub/seo/search-intent"><b>search intent</b></a>, high <b>search volume</b>, and <b>low competition</b>. 
    </p>



<h3>Tools To Help Find Potential Keywords/Keyphrase</h3>
    <ul>
        <li>
            <h4><b>Google Suggest</b></h4>
            <p>By simply typing in potential keywords or phrases into the google search bar, Google will suggest closely related searched terms. This can be a handy tool to start generating some potential keywords. 
            <img src='../images/google-suggest-results.png' alt='google suggest results'>
        </li>
        <li>
            <h4><b>Google Ads: Keyword Plan</b></h4>
            <p>Google Ads' Keyword Plan tool helps you compare search volumes and competition for keyphrases as well as generate new ideas for keywords.</p>
            <a href="../tools/keyword_plan.md">Click here</a> for instructions to navigate to Keyword Plan</p>
            <img src='../images/google-ads-keyword-plan.png' alt="results from keyword search">
        </li>
        <li>There are may other tools you can google for to help with keyword selection.</li>
    </ul>
</details>


## Front-Load Title Modifiers
<details>
<summary>Details</summary>
<br>
    <p>Title tags help Google and other search engines understand what your website is about. Titles are also what the search engine returns in big blue letters when you search a word</p>

<p>Front loading just means put your keyphrase near or at the beginning of the title.</p>
<img src="../images/front_load_titles/title-serp.png" alt="result of search engine search">

<p>
Google assumes that words and phrases coming sooner in your title have a higher priority and are more relevant to the content than words coming later. So if you want to rank for that keyword in search it is better to put it sooner in the title tag. Here are some examples for the search term "Front-Load keywords".  
</p>
<img src="../images/front_load_titles/front-loading-title-example.png" alt="examples of front loading titles">


<h3>How To Set Titles in Wordpress</h3>
    <ul>
        <li>
            <p>Either create an new pager or post or navigate to an existing page or post to edit</p>
        </li>
        <li>
            <p>In the "Add Title" section create a title</p>
            <img src="../images/front_load_titles/title-location-in-wordpress-blacnk.png" alt="location of title box">
            <p>Example: Keyphrase = Front-Load Keywords</p>
            <img src="../images/front_load_titles/title-location-in-wordpress.png" alt="title example">
        </li>
        <li>
            <p>You can also modify the title using the Yoast plugin. Scroll down until you see the yoast plugin.</p>
        </li>
        <li>
            <p>Once you find it. Click on the "SEO" tab.</p>
        </li>
        <li>
            <p>Then Click on the "Edit Snippit" button</p>
            <img src="../images/front_load_titles/yoast-title.png" alt="yoast SEO plugin location">
        </li>
        <li>
            <p>Then under the "SEO title" you can edit the title.</p>
            <img src="../images/front_load_titles/yoast-title-edit.png" alt="Yoast edit title location">
        </li>
    </ul>
</details>

## Add Meta Description
<details>
<summary>Details</summary>
<br>
<p>The <a href="https://yoast.com/meta-descriptions/">meta description</a> is a snippet of up to about 155 characters – a tag in HTML – which summarizes a page’s content. Search engines show it in search results mostly when the searched-for phrase is within the description. -exert from yoast.com</p>
<img src="../images/meta-description/meta-example.png">
<h3>How To Set URLs in Wordpress</h3>
    <ul>
     <li>
            <p>While editing an post or page, scroll down until you see the yoast plugin.</p>
        </li>
        <li>
            <p>Once you find it. Click on the "SEO" tab.</p>
        </li>
        <li>
            <p>Then Click on the "Edit Snippit" button</p>
            <img src="../images/front_load_titles/yoast-title.png" alt="yoast SEO plugin location">
        </li>
        <li>
            <p>Then under the "SEO title" you can edit the meta tag. You should include keywords or synonyms in the meta description.</p>
            <img src="../images/meta-description/meta-yoast-edit.png" alt="Yoast edit meta tag location">
        </li>
    </ul>
</details>

## Include Keyphrase in URL
<details>
<summary>Details</summary>
<br>
    <p>
    We want our url to contain our keyphrase. So if your keyphrase is "front-load keywords" our url should at least contain the keywords. "www.examplecompany.com/front-load-keywords" would work. Your url can contain extra words but try to keep it concise. If this web page is under a sub category of the website such as blogs the url would look something like "www.examplecompany.com/blog/front-load-keywords"
    </p>

<h3>How To Set URLs in Wordpress</h3>
    <ul>
        <li>
            <p>Wordpress trys to auto generate you a URL based off the title. If you title is relatively short and contains your keyphrase, then you are probably good to go. If it doesn't refactor your title to contain your keywords or shorten your URL while retaining the keywords. Do not have unnecessarily long URK=Ls (over 5-6 words).</p>
            <img src="../images/front_load_titles/keyword-url.png" alt="keyword in url">
        </li>
        
    </ul>
</details>




## Embed Title Tag Modifiers
<details>
<summary>Details</summary>
<br>
<p>Title Tag Modifiers are words that add detail to your title tag</p>
<p>If your site was a recipe site and the keyphrase was: "home-made pizza recipe " modifiers would be works or phrase like: best, 2021, in 5 steps, quick and easy, ect.</p>
<p>So the the entier title would could look like this:</p>
<ul>
    <li>Best Home-Made Pizza Recipe</li> 
    <li>Home-Made Pizza: 2021's Best Recipie</li> 
    <li>Home-Made Pizza Recipe in 5 Easy Steps</li> 
</ul>
<p>Adding modifiers can make your website rank for <a href="https://yoast.com/focus-on-long-tail-keywords/">long-tail keyphrases</a> but they also help your click through rate. These modifiers make your title more interesting am more likely to be clicked.</p>

<p>Would you click on "Pizza Recipe" or "Pizza Recipe: 2021's Most Delicious Recipe in 5 Steps</p>
</details>


## Include Keyphrase In First 150 Words
<details>
<summary>Details</summary>
<br>
<p>Make sure your keyphrase appears in the first 150 or so words of the content</p>
<p>Google scans the content of each web-page. If it doesn't see your keyword in the beginning it can be confused about what the topic of the content is.</p>

<p>If a speaker was on-stage for 30 minutes before he told you what the speech was about you would be confused. Don't do that with your content, let the read and google know right away what the page is about. </p>
</details>


## Include Keyphrase In h1 element
<details>
<summary>Details</summary>
<br>
<p>HTML is the standard markup language for creating Web pages. In HTML, the h1 element is the top level heading of a web page similar to the title of an essay. For example the h1 element for this web page is &lt;h1&gt; Keyword and On-Page SEO Checklist &lt;/h1&gt;. Just like the title of a paper the h1 element tell the user and google what the web page is about. The h1 needs to include the keyphrase. There can be other words included with the keyphrase and the keyphase can even be reorder but make sure to include it.</p>

<h3>How To Set URLs in Wordpress</h3>
   <p>In most causes the "Title" of the page or post will automatically become the H1. So include the keyphrase in the title.</p>


</details>

## Each Page Can Only Have One h1 element
<details>
<summary>Details</summary>
<br>
<p>Pages should only have one h1 element per page but you can have as many h2, h3, h4, ect elements as you would like. If you have multiple h1 google has a harder time figuring out what your page is about and this will negatively effect your ranking</p>

<p>The yoast plugin on wordpress will tell you if you accidentally made a page with multiple h1 elements. If you did, you can go back in the editor and delete the extra h1 or change it to an appropriate sub heading like an h2 or h3</p>

<p>
    If you use the visual builder, the title will become the h1 tag. In the content area, make sure you only use headings of "Heading 2" or larger for all sub headings. If you use "Heading 1" it will create another h1 element and we only want one h1 element per page.
    </p>
    <img src="../images/h1/correct-h-elements-builder.png">
    <img src="../images/h1/correct-h-elements.png">

<p>Occasionally yoast will tell you that you have multiple h1 elements when you don't. Here is a way to triple check</p>

<ul>
    <li>Open Google Chrome</li>
    <li>Go to the url of the webpage Yoast says has multiple h1 element</li>
    <li>Once on the web page, right click anywhere on the page</li>
    <li>Click the Elements tab from the horizontal navigation bar</li>
    <li>Then click control+f on the keyboard to bring up a search box</li>
    <li>search for &lt;h1&gt;</li>
    <li>If the results show only 1 item you are good. If multiple show, find them and refactor the headers in wordpress</li>
</ul>

</details>

## User Keyphrase In h2 And h3 Tags If Practical
<details>
<summary>Details</summary>
<br>
<p>If the h1 element is the title of a paper, h2 is the the title of the sub topics.<p>

<p>If practical, include the keyphase or parts of it or synonyms in the h2 and h3 tags</p>

<p>Never keyword stuff. This is when you put the keyword everywhere even in places it doesn't fit to try to increase you ranking for that keyword. </p>

<p>This doesn't work and can actually <b>HURT YOU SEO</b>. Google can identify keyword stuffing and can lower your rank thinking your website is a span site trying to hack or cheat the system</p>

<p>Always choose heading and sub heading that best convey the message of the content to the user regardless of if it contains keywords.</p>
</details>



## Make Sure Images Have Descriptive File Names
<details>
<summary>Details</summary>
<br>
<p>When you load media: photo, videos, gif, ect into wordpress. It is best practice to have descriptive filename. Kebab case, all letters are written in lower case and the words are separated by a hyphen or minus sign is the standard naming format.</p>
<p>So this photo file name should be something like dog-chasing-tail.jpg not an auto generated name like FDGZmicro_20150424GettyImages_dv413023_MAIN (1).jpg and you should aviod spaces in file names like dog chasing tail.jpg </p>
<img src="../images/file-names/dog-chasing-tail.png" alt="dalmatian chasing its tail">
<p>Google does not have eyes, well at least not yet. So it uses the file names to gain insite about what media contains. Descriptive names help google understand what the photo is about as well as how it supports your content.</p>
<p>Plus it is just easy to find and navigate your media when it has human readable names.</p>

<p>Kebab case is the standard name formatting. Kebab case uses dashes where spaces would be so</p>
</details>


## Add Alt Text To All Images That Are Not Soley Decorative
<details>
<summary>Details</summary>
<br>
<p>Alt Text (also known as alternative text or alt attribute) is a text that accurately describes an image. It is added to the <img> tag in the HTML of a page. </p>

<p>The alt text is not shown when a page is viewed in the browser but it becomes visible when an image cannot be loaded.
</p>
<p>
Search engine crawlers read the alt text value and screen readers use it to ‘describe’ the image to users who cannot see.</p>

<h3>How To Add Atl Text To Images in Wordpress</h3>
<p>There are multiple ways to do this depending on how you build the content. I will go over the one I know</p>

<ul>
    <li>
        <h4>Add Media</h4>
       <p>Clicking the "add media" button will bring you to image options</p>
       <img src="../images/alt/add-media.png">
       <p>Then in the alt text box you can add alternet text.</p>
       <img src="../images/alt/alt-text-edit-location.png">
       <p>Now you can insert the photo.</p>
    </li>
    <li>
        <h4>Editing Existing Photos' To add Alt Text</h4>
       <p>If a photo is already in a post or page using the visual builder, you can click on the image and then on the pencil icon to edit the detail.</p>
        <img src="../images/alt/edit-alt-text.png" alt="edit image button">
        <p>Add or Update the alt text and then click update to save the changes.</p>
         <img src="../images/alt/update-and-save-alt-text.png" alt="update alt text">
    </li>
    <li>
        <h4>Editing Alt Text For Photos in Divi Builder</h4>
        <ul>
            <li>Under the divi builder for the page you are working on. Find or insert an image</li>
            <li>
                <p>Click to more options button and then select "Modify Default Values"</p>
                <img src="../images/alt/div-img-more-options-button.png">
            </li>
            <li>
                <p>Exit out of the "Default Image" tab that pops up by clicking the red X at the bottom left</p>
                <img src="../images/alt/img-defualts.png">
            </li>
            <li>
                <p>When the Image Setting page pops up, click the "Advanced" tab</p>
                <img src="../images/alt/div-image-settings.png">
             </li>
             <li>
                <p>Click the "Attributes" tab and then the alt text box will appear. Add your alt text and click the green check to save</p>
                <img src="../images/alt/div-alt-text-location.png">
             </li>
             <p>If you use the "build on front end" build option, the steps to add alt text are similar to the divi builder</p>
        </ul>
    </li>
</ul>
</details>


## Keyword Density, Synonyms and LSI Keywords In Content
<details>
<summary>Details</summary>
<br>
<p>Make sure that we are organically using the keyword, synonyms, or <a  href="https://ahrefs.com/blog/lsi-keywords/">LSI keywords</a> thought the content. We don't have to go crazy but if the article is 1000 words, we would expect to see the keyword, synonyms  or lsi words 3-5 times</p>
</details>


## Use External Links
<details>
<summary>Details</summary>
<br>
<p>It is recommend to have external links to trusted site. So if you can link to wikipidia or a research study related to the the content it helps google know our content it quality and relying on trustworthy sources.</p>

<p>Good content often requires good sources. Naturally if you are realaying on trusted sources to support your content claims you would be able to provide them as reference. This is the though process behind having external links.</p>
</details>


## Use Internal Links
<details>
<summary>Details</summary>
<br>
<p>Internal links show how our pages are connected. It is good practice to link to other internal pages when they contain relevant but extend or more in-depth content related to our topic. Google looks at which pages have the most internal links pointing to them and assess those are our most important pages. </p>
</details>

