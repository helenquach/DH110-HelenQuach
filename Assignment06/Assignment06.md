# Assignment 06: Interface Design
Helen Quach | DH 110 | Fall 2022

## Project Description
The goal of this project is to design a website that provides people with the resources to learn about one of the United Nations' Sustainable Development Goals, Goal #11: Sustainable Cities and Communities. The website will feature a News page where users can easily access the latest relevant news regarding environmental sustainability. The website will also feature a social aspect on the Community page, where users can interact with one another in a forum and ask questions about living a sustainable lifestyle, read reviews of local businesses, and recommend tips. I decided to name the website Greenforum (stylized "greenforum") to combine the forum aspect of the website with the "go green" mentality of sustainable living.

### Purpose of interface design
The purpose of interface design is to start the process of digitizing your low-fidelity prototype and develop a design system of fonts, shape, colors, and spacing that you can use in your future designs. In the process, you can also learn how users may perceive your design at first glance and adjust your design as necessary.

### Design process
I used Figma to digitize my low-fidelity prototype. I used the Macbook Pro 14" size for my frames, which is 1512 x 982 pixels. I began by deciding on the spacing of my grid and then laying out the basic shapes from my wireframe, choosing colors as I went. Then I decided on a typography system from a variety of options. I also tested different shapes for the elements on my website such as the news cards and the social media bar. Finally, I tested various color schemes and developed a dark mode color scheme.  

### Example wireframe
Below is the example wireframe that I digitized as part of my interface design.
![example-wireframe](../Assignment05/wireflow-1.JPG)

From the initial wireflow testing, I discovered that the pull-up social media menu was not intuitive and decided to implement instead a social media bar on the side of the page that will stay in place as the user scrolls through news articles.

### Link to prototype
Here is the [link to the Figma file.](https://www.figma.com/file/7bqPEgQ3nS4W1Bl99qofRQ/DH-110-Interface-Design-System?node-id=0%3A1)

Here is the [link to the prototype.](https://www.figma.com/proto/7bqPEgQ3nS4W1Bl99qofRQ/DH-110-Interface-Design-System?node-id=104%3A2495&scaling=min-zoom)

## Screen Design

### Typography variations

I tried a variety of typography options, including sans serif and serif fonts for the headline and body text. The options explored can be seen below. 

#### Variation 1: Urbanist
![typography-1](typography-1.png)

#### Variation 2: Archivo
![typography-2](typography-2.png)

#### Variation 3: Zilla Slab
![typography-3](typography-3.png)

#### Variation 4: Fraunces, Work Sans
![typography-4](typography-4.png)

In the end, I settled on using the fonts Fraunces for headline text and Work Sans for body text. 

### Shape variations

I explored different shapes for the news card element and social media bar elements. First I tried rounded rectangles with 32px radius. Then I explored rectangles with 0px radius for sharper corners and a more refined look. I also tried a custom shape with varied radii (32px, 0px) that represents the leaf in the logo that I designed for the website. In the end, I decided to use the rounded rectangles with just 32px radius, because the consistent radius looked more trustworthy.

#### Variation 1: 32px radius
![shape-1](shape-1.png)

#### Variation 2: 0px radius
![shape-2](shape-2.png)

#### Variation 3: Varied (32px, 0px) radius
![shape-3](shape-3.png)

### Color variations

I initially created a green color scheme for the website to compliment the logo and the name of the website, Greenforum. I experimented with a brown version, since brown and green are often seen together in nature. However, I thought that the green version was more elegant. I also developed a dark mode to compliment the green version of the website, shown below.

#### Variation 1: Green
![color-1](color-1.png)

#### Variation 2: Brown
![color-2](color-2.png)

#### Variation 3: Green Dark Mode
![color-1-dark-mode](color-1-dark-mode.png)

### Layout testing
I designed my layout according to the grid shown below.
* 7 columns, 32px margin, 48px gutter
* 10 rows, 0px margin, 24px gutter


![layout-test](layout-test.png)

## Impression Test

I showed my prototype to another person for 5 seconds and asked them to recall anything they could remember about the website. Then I gave them the prototype to play around with and asked them for their thoughts on the fonts, colors, layout, and overall design. Here are the results:

### Audio recording
Here is the [audio recording of the impression test.](https://drive.google.com/file/d/1C0qJg82TzCWPy53P63ZdqNgC-h0an03H/view?usp=sharing)

### Transcript
Here is the [transcript of the impression test.](https://docs.google.com/document/d/1yTgQgTlz9ikaSWJ9oqvASm2xmSKX6lkv8ZmoXhUi4uQ/edit?usp=sharing)

### Findings
From the 5-second test:
* Website appears to be about nature
* Overwhelmingly forest green colors
* Social media side bar was very prominent
* Everything was grouped together and organized well
* Three columns, easy to read

Other findings:
* Having elements change color on hover is a useful visual feature
* Should add some kind of interactive element to page numbers at bottom of news articles
* Should make the search icon bigger
* Good contrast between typography choices for headline and body text

After the impression test, I made the search icon bigger and plan to implement more interactive elements throughout the website. I also decided to make the wordmark of my logo one color instead of two so that it is easier to read.

## Accessibility Check

I performed color contrast checks for the light mode and dark mode versions of my design. All color combinations of text and background color passed the 4.5:1 ratio test, as shown below.

### Light mode
![color-1](color-1.png)
<img src="color-contrast-check-1.png" width="500">
<img src="color-contrast-check-2.png" width="500">

### Dark mode
![color-1-dark-mode](color-1-dark-mode.png)
<img src="color-contrast-check-3.png" width="500">
<img src="color-contrast-check-4.png" width="500">

## Design System
### Final prototype
![final-prototype](final-prototype.png)
### Layout test
![layout-test-2](layout-test-2.png)

### Typography
|   | Font | Weight | Size | Letter spacing |
| --- | --- | --- | --- | --- |
| Headline 1 | Fraunces | Bold | 108px | -1.5px |
| Headline 2 | Fraunces | Bold | 68px | -0.5px |
| Headline 3 | Fraunces | Bold | 54px | 0px |
| Headline 4 | Fraunces | Bold | 38px | 0px |
| Headline 5 | Fraunces | Bold | 27px | 0px |
| Headline 6 | Fraunces | Bold | 23px | 0px |
| Subtitle 1 | Fraunces | SemiBold | 18px | 0px |
| Body 1 | Work Sans | Regular | 17px | 0.5px |
| Body 2 | Work Sans | Regular | 15px | 0.25px |

Note: For body text, use 150% for line height.

> I chose to use the font Fraunces, a serif font, rather than other sans serif fonts, for the headline text because it looks more trustworthy for a source of news. Newspapers are printed in serif fonts, so I chose to use a serif font to emulate that. However, this font is not easy to read when it is small, so I chose Work Sans, a cleaner sans serif font to use for the body text. The combination of a serif and sans serif font provides a nice contrast and creates a modern look. This is important, because the target users of my website are young adults. I want to be able to appeal to my target users by appearing modern and up-to-date, but still trustworthy as a news source.

### Color scheme
#### Light mode
* Background color, text: FCFDFC
* Lines: DDDDDD
* Secondary background color: EFF5F3
* News card, text: 355A4B
* Social media bar, footer: 11422D
* News card, social media links on hover: 99D16D

#### Dark mode
* Background color, text: 09100D
* Lines: 264036
* News card, secondary background color: 1C3028
* Social media bar, footer, text: 4CA464

> I wanted to use a mainly green color scheme to emphasize the "go green" mentality of sustainable living as well as the namesake of the website, Greenforum. Green also represents nature and is generally a calming color. I want people who enter the website to feel calm, relaxed, and safe. Therefore, I chose to use a green color scheme for the website. The specific shades of green were chosen from the original logo that I designed for the website. 

### Layout grid and spacing
* 7 columns, 32px margin, 48px gutter
* 10 rows, 0px margin, 24px gutter

> I chose this layout grid and spacing based on the wireframes that I designed during my low-fidelity prototype development. I chose numbers that were multiples of 8 or 16 so that they would work well with the size of the body text.
