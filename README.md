# Silver Eagles Engineering Portfolio 2023-2024

This is the nice looking Engineering Portfolio for this season. It's made using Adobe InDesign. In order to update it, you'll need to use InDesign, though some programs are capable of reading `.indd` files, but I haven't tried them.

The `/images` folder contains all the images used in the document. InDesign files need to know where the images are coming from, so it's good practice for images and the document to be in the same folder.

I figure git is a good place to store it because git maintains a version history and could (in theory) be a better way to have multiple people work on it; better than having to keep emailing the file to each other.

## Use This As A Template
Feel free to make a template out of this for future seasons!

**My recommendation is that every season we still should create a Google Doc.** We can use Google Docs as a way to write up all the content that will go in our engineering portfolio.

After the content is written / planned, then we use InDesign to make it pretty. InDesign is only good to make documents look pretty; it's a bad program to plan out what content you're going to write because: 1) it's not easily collaborative (can't have multiple people working at once), and 2) content doesn't flow from page-to-page. You set all the content, and how it's placed and looks, on each page manually.

So after the team is (relatively) happy with the portfolio content before the competition, have someone place that content nicely using InDesign. It takes time though; the person putting setting the content in InDesign should have at least a week to do so.

Also, I recommend backing up the InDesign doc in Github.

_Note_: InDesign is part of the Adobe Creative Cloud Suite. There are student discounts, but it's still a bit pricey. We should pester the school (or use our budget), to get access to it.

## Fonts Used

- **Roboto Slab**
  - We're using this for titles, headings, and subheadings
  - This is a free font from Google Fonts:
    - https://fonts.google.com/specimen/Roboto+Slab
  - Weights used:
    - Black (it's like super bold)
    - Semibold
    - Bold
- **Monsterrat**
  - We're using this for all content text
  - Also a free font from Google Fonts:
    - https://fonts.google.com/specimen/Montserrat
  - Weights used:
    - Regular (this is weights good for paragraphs)

_Note_: You need to download and install these fonts from the above links to be able to use them on your machine (and thus, also in the document).

## Colors Used

| Hex Code | Preview | Use Case |
|:--:|:--:|:--:|
|`#084887`|<a href='#'><img valign='middle' src='https://readme-swatches.vercel.app/084887'/></a>|• Titles <br>• Main Section Names (Heading 1s) <br>• Page Number Backgrounds|
|`#70a7cb`|<a href='#'><img valign='middle' src='https://readme-swatches.vercel.app/70a7cb'/></a>|• Subheaders (Sub sections / Heading 2s)|
|`#c6dff2`|<a href='#'><img valign='middle' src='https://readme-swatches.vercel.app/c6dff2'/></a>|• Cover Page Boxes <br> • Team Name + Number in page header|
|`#000000`|<a href='#'><img valign='middle' src='https://readme-swatches.vercel.app/000000'/></a>|• Used for page content (paragraph text)|


## Folder Structure

- `.gitignore` - I added this so it ignores a junk file (`.DS_Store`) added by OS X
- `images/` - Where our images used in the document go
- `2024 Engineering Portfolio.indd` - This is the InDesign file. This has all the page layouts, colors used, etc. When we need to make a change to the document, we'll edit this file and then export a new PDF.
- `2024 Engineering Portfolio.pdf` - The exported PDF. This is what we print out and hand in to the judges.
- `README.md` - The file you're reading now (: (probably reading it through Github)
- `~2024 engineering port~16())2.idlk` - Anything that ends in `.idlk` is a temporary file that's present while you have an InDesign document open on your computer. It's basically junk, but probably best to not delete it manually because InDesign will probably handle that when you close the program.

## Notes

- Use Adobe Express [Background Tool Remover](https://new.express.adobe.com/tools/remove-background) to remove the background from images and make the backgrounds transparent
- The Github preview of our PDF looks a little weird than how the PDF actually renders when it's downloaded on your machine or printed
- Font weights specify how thick the font should be
