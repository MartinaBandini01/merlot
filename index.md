<!DOCTYPE HTML>
<!--
	Massively by HTML5 UP
	html5up.net | @ajlkn
	Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)
-->
<html>
	<head>
		<title>Fashion</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>
	</head>
	<body class="is-preload">

		<!-- Wrapper -->
			<div id="wrapper" class="fade-in">

				<!-- Intro -->
					<div id="intro">
						<h1>Decoding High Fashion<br />
						A Data-Driven Exploration of Gucci, Prada, & Dior</h1>
						<p>Unveiling the hidden narratives and comparative landscapes of luxury fashion through the power of semantic web technologies and AI.
							
						</p>
						<ul class="actions">
							<li><a href="#header" class="button icon solid solo fa-arrow-down scrolly">Continue</a></li>
						</ul>
					</div>

				<!-- Header -->
					<header id="header">
						<a href="index.html" class="logo">Fashion</a>
					</header>

				<!-- Nav -->
					<nav id="nav">
						<ul class="links">
							<li class="active"><a href="index.html">FASHION</a></li>
							<li><a href="generic.html">SPARQL QUERIES</a></li>
							<li><a href="elements.html">LLM PROMPTS</a></li>
						</ul>
					</nav>

				<!-- Main -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Knowledge Project: Wikidata & LLMs</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font import for a polished look */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        /* Base styles for the body to ensure full screen and B&W theme */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f8f8; /* Very light gray background */
            color: #333333; /* Dark gray for main text */
            margin: 0; /* Remove default browser margin */
            padding: 0; /* Remove default browser padding */
            min-height: 100vh; /* Ensure body takes at least full viewport height */
            display: flex; /* Use flexbox for centering content */
            flex-direction: column; /* Stack content vertically */
            align-items: center; /* Center content horizontally */
        }

        /* Styling for links to maintain the black and white theme */
        a {
            color: #555555; /* Darker gray for links */
            text-decoration: underline;
            transition: color 0.2s ease-in-out; /* Smooth transition for hover effect */
        }
        a:hover {
            color: #000000; /* Black on hover */
        }
        
        /* Styling for horizontal rules */
        hr {
            border-color: #e5e7eb; /* Light gray border for dividers */
            border-width: 1px;
            border-radius: 9999px; /* Full rounded corners for the line */
        }

        /* Responsive adjustments for headings and text size */
        @media (min-width: 768px) { /* Medium screens and up */
            .text-4xl { font-size: 3rem; } /* Adjust main title size */
            .text-5xl { font-size: 3.75rem; } /* Adjust main title size on larger screens */
        }

        /* Styling for the brand logos */
        .brand-logo {
            width: 80px; /* Adjust as needed */
            height: auto;
            margin-right: 15px; /* Space between image and text */
            vertical-align: middle; /* Align image with text */
            border-radius: 0.25rem; /* Small rounded corners for images */
            box-shadow: 0 1px 3px rgba(0,0,0,0.1); /* Subtle shadow for images */
        }
    </style>
</head>
<body>
    <!-- Main content container that holds all project information -->
    <div class="bg-white shadow-lg p-10 md:p-12 w-full max-w-screen-xl mx-auto rounded-lg">

        <!-- Project Title -->
        <h1 class="text-4xl md:text-5xl font-extrabold text-center text-gray-900 mb-8">
            Our Fashion Project: Wikidata & LLMs
        </h1>

        <!-- Welcome Section -->

---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
