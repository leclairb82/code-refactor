# Code Refactor

<br>

## Description

the goal of this project was to take an existing websites code and refactor it so that it is accessible to the end user. When I view the source code, I found many non-semantic elements that were converted to semantic elements (ie; div to main, or div to figure). When I viewed the structure of the HTML elements I found instances where a div tag was used when it would be more logical to use something more descriptive, like nav or main; this allows someone to easily know what is what. I also removed redundant id attributes that were not necassry for styling. When I viewed the image elements I found no alt tags; alt tags were added so that if the image is not displayed the user has alternative information to rely upon. When I viewed the heading attributes I found an instantance of non-sequential order, the footer header tag as h2 doesn't make sense, h4 will make text smaller, and for a footer that is ideal. When I viewed the title element w/ in the head, I did not find a desciptive title; The title was changed so that the text in the browser tab is clear and concise. Lastly I implemented the scout rule to clean up the structure of the code to make it easier to read and navigate.

<br>

## Code Snippet
```html
    <header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
```

<br>

## Lists
- Search Engine Optimization
- Online Reputation Management
- Social Media Marketing

<br>

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

<br>

## Deployed Link

* [See Live Site](#)


## Authors

* **Brett LeClair** 

- [Link to Portfolio Site](#)
- [Link to Github](https://github.com/leclairb82/)
- [Link to LinkedIn](www.linkedin.com/in/brett-leclair-71a8bab)


