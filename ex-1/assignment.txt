1. Differences Between HTML Tags
i. <strong> vs. <b>
<strong> (Semantic): This is an indication of importance, seriousness, or urgency. Screen readers will often change the tone of voice to emphasize this text. It tells the browser and search engines that this content is fundamentally important.

<b> (Presentational): This stands for Bold. It is used purely for stylistic purposes to draw attention to text without adding any extra importance. Use this when you just want a word to look "thick" but it doesn't carry special weight.
+1

ii. <em> vs. <i>
<em> (Semantic): This stands for Emphasis. It indicates a stressed emphasis that changes the meaning of a sentence (like how you'd change your pitch when speaking).

<i> (Presentational): This stands for Italic. It is used for text that is set off from the normal prose for a different reason like a technical term.

Note: Use <strong> and <em> by default. Only use <b> and <i> as a last resort when there is no semantic meaning attached to the style.

2. What is Semantic HTML?
Semantic HTML is the practice of using HTML tags that accurately describe the meaning of the content they contain, rather than how that content should look.

For example, instead of using a <div> for everything, you use specific tags like <header>, <nav>, <main>, and <footer>.

Importance of Semantic HTML
Accessibility (A11y): Screen readers use these tags to help visually impaired users navigate a site. A user can "jump" to the <nav> or <main> section easily.

Search Engine Optimization (SEO): Google’s crawlers prioritize content wrapped in semantic tags. It helps the engine understand what your page is actually about.

Code Readability & Maintenance: For you and your fellow developers, it is much easier to read a file full of <article> and <section> tags than a "div-soup" where everything is just a <div>.

Consistent Styling: It makes it easier to target specific parts of your document in CSS without needing a million different class names.