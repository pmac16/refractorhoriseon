# Refactor Project for Horiseon

## Description

Horiseon, a marketing agency, has asked me to refactor their site to make it more accessible.

Making a website more accessible is critical for people with disabilities to engage meaningfully with a website. In addition, this allows Horiseon to be better positioned in search engines.

```
User Story

AS A developer
I WANT to refactor a codebase that follows accessbility standards
SO THAT my client, Horiseon's, website is optimized for search engines
```

I added semantic HTML elements, ensured that they followed a logical structure, added accessible alt attributes, and a concise, descriptive title. In addition, some aspects of code were cleaned up. Below is a detailed description of what changes were made.

You can view the deployed website here: 

## Table of Contents

* [Logical HTML Structure](#LogicalHTMLStructure)
* [Accesible Alt Attributes](#AccessibleAltAttributes)
* [Title](#Title)
* [Additional Changes](#AdditionalChanges)

### Logical HTML Structure
Originally, the HTML code included many div sections without any semantic elements. The code was restructured to follow a logical HTML structure with semantic elements. The elements used were header, navigation, article, aside, and footer. 

The CSS class names were then changed to follow the names of the semantic elements as well. The CSS code was also reordered so that it followed the same order as the HTML code.

Finally, the footer heading was changed so that it would be read last (h2 to h4).

```md
![Header] (assets/images/screenshot.header.png)
![Article/Aside] (assets/images/screenshot.footer.png)
![Footer] (assets/images/screensht.header.png)
```

### Accessible Alt Attributes
All images on this site did not have accessible alt attributes. The Search Engine Optimization image, Online Reputation Mangement image, and Social Media marketing image all received descriptive alt attributes. The images within the aside section received alt"" attributes as they were decorative.

### Title
The original title was unoriginal, and just stated "website." That was updated to include the company name, Horiseon.

### Additional Changes

The link to the Search Engine Optimization was broken. It was missing an ID, which was added on line 38.

CSS selectors were combined if they had similar properties. Instead of each heading having it's own class, they were combined. For example, all the img classes were grouped together. 

Overall, there were not a lot of comments to help with organization. Comments were added to show when sections start and end.
