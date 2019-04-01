# Primer Presentations
**Get the templates:** [Keynote](https://drive.google.com/open?id=1OSiR4aPmVZ3UKbLsHIDpoVILYU1Zx3tp) | [Google Slides](https://docs.google.com/presentation/u/0/?tgif=d&ftv=1) | [Figma](https://www.figma.com/file/0mXCPvPvDgbtiMEIa5Z8DSh9/GitHub-Presentation-Template?node-id=267%3A0)

_Last updated: March 22, 2019_

<img width="1012" alt="presentation-teampost" src="https://user-images.githubusercontent.com/10384315/55268551-ec2c6980-5247-11e9-8769-cc8949a453d9.png">

**Table of Contents**
- [Introduction](#introduction)
- [Presentation formats](#presentation-formats)
- [Design guidelines](#design-guidelines)
- [Slide types](#slide-types)
- [Resources](#resources)
- [Versioning](#versioning)

# Introduction
Primer Presentations is the presentation design system for GitHub. This repo contains the presentation themes, guidelines, and assets needed in order to create a presentation that represents the GitHub brand.

**Basic Principles**
- **You're a storyteller.** When you give a presentation, you're not just sharing data and analysis, you're also telling a story with a unique and important message.
- **Slides aren't everything.** Your slides are meant to support your presentation. But don't depend on them to the point where you're cramming every idea in your brain into text on the slide. When it comes to adding text, remember that less is more. If you find yourself with too much text, ask yourself, "What is my key message?"
- **Be concise.** Keep your content short and direct. Too much text creates a conflict for the audience as they are stuck between reading what's on the slide and listening to what you have to say. Instead of paragraphs of text, use a few bullet points to supplement your message.

---

# Presentation Formats
We support the following presentation formats:
- [Keynote](#keynote)
- [Google Slides](#google-slides)
- [Figma](#figma)

If there are any inconsistencies or bugs, please [submit and issue](https://github.com/primer/presentations/issues/).

## Theme templates

Primer currently has one official theme available that we support, the **GitHub Presentation template**. This theme was created with the purpose to support the internal presentations within GitHub.

### Keynote
The GitHub presentation template is available as both a Keynote deck and as a Keynote theme. They are available for download to the members of the GitHub organization on [Google Drive](https://drive.google.com/open?id=1OSiR4aPmVZ3UKbLsHIDpoVILYU1Zx3tp).

**Need help?** Read the [installation instructions](keynote-instructions.md).

### Google Slides

The GitHub presentation template is available for use in the Google Slides template gallery.

![googleslides](https://user-images.githubusercontent.com/10384315/55342464-b95bbe80-545d-11e9-8897-b311cc51f489.gif)

### Figma
The GitHub presentation theme is available as a Figma library for members of the GitHub organization.

To use, enable the GitHub Presentation Template in the Team libraries.
![figma](https://user-images.githubusercontent.com/10384315/55271261-0fb2dc80-5267-11e9-94bd-5268f1e2f9fb.gif)

For more information on using Figma libraries, please refer to [Figma's documentation](https://help.figma.com/article/29-team-library).

---

# Design Guidelines

## Text styling
The presentation system uses system fonts. The default font is **Helvetica Neue**. The default monospace font is `Menlo` in Keynote and `Roboto Mono` in Google Slides.

### Font Sizing
|   Type  | Keynote | Google Slides |
| :-----: | :-----: | :-----------: |
|    H1   |   100   |      40       |
|    H2   |   72    |      30       |
|    H3   |   64    |      24       |
|    H4   |   56    |      18       |
|   Body  |   48    |      16       |

### Monospace Fonts
Monospace fonts are used for quote attributions, code, and labels/eyebrow text.

### Highlighting
Highlighting is great for indicating important points that you'd like your audience to remember from a statement or quote. In our system, highlights are represented by altering the color of the text.

**Usage guidelines:**

- **Avoid multiple highlights.** Highlights should be used sparingly to only highlight key words or phrases on the slide. Too many highlights will confuse your audience in regards to what the most important take away should be.
- **Emphasis over decoration** Remember that when you're highlighting text you're telling the audience, "This is important". Be sure to ask yourself "Is the highlight necessary to add emphasis to my talking point?" before highlighting.

Do ✅ | Don't 🚫
:---: | :---:
![quote-good](https://user-images.githubusercontent.com/10384315/55268057-cef59c00-5243-11e9-8400-6381fae36fea.png) | ![quote-bad](https://user-images.githubusercontent.com/10384315/55268059-d7e66d80-5243-11e9-9842-37d4009dfb9e.png)
Highlight important points that your audience should pay attention to. | Use too many highlights.





#### Recommended highlight color pairings

All highlight colors come from the [Primer color system](https://styleguide.github.com/primer/support/color-system/). We've supplied a list of recommended highlight colors below.

|   Background  |  Highlight  | Hex value |
| :-----------: | :---------: | :-------: |
|     Black     |  yellow-400 |  #ffdf5d  |
|     Black     |   blue-400  |  #2188ff  |
|     Black     |   red-400   |  #ea4a5a  |
|     White     |   blue-600  |  #005cc5  |
|     White     |   red-500   |  #d73a49  |


## Images
When using a screenshot, it’s best to match the background. We suggest to take a screenshot on a similar color background or use a PNG with a transparent background as this will look the most seamless.

### Usage guidelines:

Do ✅ | Don't 🚫
:---: | :---:
<img width="500" alt="image-white" src="https://user-images.githubusercontent.com/10384315/54647439-b32e1100-4a5f-11e9-8d85-a4a2e64319ca.png"> | <img width="500" alt="image-black" src="https://user-images.githubusercontent.com/10384315/54647548-1f107980-4a60-11e9-9640-8f1721609e44.png">
Use images with a similar or transparent background. | Use images with opposite backgrounds to the slide background.

### Adding images

Images can be easily added to any presentation by simply drag and dropping, copy and pasting, or inserting from the toolbar in Keynote, Google Slides, and Figma.

#### Adding images in Keynote

|    Source   |  Description  |  Example  |
| :---------: | :-----------: | :-------: |
| Browser | Drag and drop any image from the web browser into Keynote | ![keynote-image-web](https://user-images.githubusercontent.com/10384315/54856849-b6243e00-4cb9-11e9-8eb1-43cdb86a6fb1.gif) |
| Local machine | Drag and drop any image from the Finder into Keynote | ![keynote-image-finder](https://user-images.githubusercontent.com/10384315/54856962-2af77800-4cba-11e9-92e4-5e80d02818dc.gif) |

#### Replacing images in Keynote
|    Step   | Example  |
| :---------: | :-------: |
| Select the image and click the `Image` tab | ![keynote-image-replace-1](https://user-images.githubusercontent.com/10384315/54857498-d7d2f480-4cbc-11e9-9f53-8e1945758d41.gif) |
| Click the `Replace` | ![Screenshot 2019-03-22 16 05 39](https://user-images.githubusercontent.com/10384315/54857393-5a0ee900-4cbc-11e9-8e73-802d195c424c.png) |
| Select the new image and click `Open` | ![keynote-image-replace-3](https://user-images.githubusercontent.com/10384315/54857324-f8e71580-4cbb-11e9-9570-8d5022954806.gif) |

#### Adding images in Google Slides

|    Source   |  Description  |  Example  |
| :---------: | :-----------: | :-------: |
| Browser | Drag and drop any image from any tab in your web browser into the tab with Google Slides | ![google-slide-add-image-3](https://user-images.githubusercontent.com/10384315/54857774-5d0ad900-4cbe-11e9-8eee-25caa07a47aa.gif) |
| Local Machine | In the toolbar select `Insert > Image > Upload from computer` | ![google-slide-add-image-1](https://user-images.githubusercontent.com/10384315/54857772-5c724280-4cbe-11e9-8db6-2a4479eb2048.gif) |
| By URL | In the toolbar select `Insert > Image > By URL` and paste the image's URL | ![google-slide-add-image-2](https://user-images.githubusercontent.com/10384315/54857773-5d0ad900-4cbe-11e9-97cd-72d17e10c485.gif) |

#### Replacing images in Google Slides
|    Step   | Example  |
| :---------: | :-------: |
| With the image selected, click the `Replace Image` in the toolbar | ![Screenshot 2019-03-22 16 33 02](https://user-images.githubusercontent.com/10384315/54858122-2cc43a00-4cc0-11e9-9dd7-84eccb7128e2.png) |
| Select which method to replace your image | <img width="500" alt="google-slide-replace" src="https://user-images.githubusercontent.com/10384315/54858092-f686ba80-4cbf-11e9-821d-dfc9febc02e8.png"> |


## GitHub Icons and Illustrations
You are allowed to use certain illustrations provided by our awesome creative team in your presentation. Please _**only**_ use approved art provided within the [Asset Library](). If you cannot find what you are looking for or would like to request something specific, please create an issue within the [presentations repo](https://github.com/primer/presentations/).

**A few guidelines**
- **Don't** alter the illustrations.
- **Don't** combine images that use different stylings

### Icons
Icons are used to show a visual association with different objects (e.g., The core four include: Developers, Teams, Enterprise, and Maintainers). There are two sets of icons specific to GitHub: the [GitHub marketing icons](https://primer.github.io/presentations/assets-list.html#marketing-icons) and the [Octicons](https://octicons.github.com/).

<img width="958" alt="Screenshot 2019-03-29 17 32 58" src="https://user-images.githubusercontent.com/10384315/55268614-b340c480-5248-11e9-9600-03b5bb7e6073.png">

#### Replace icons (Keynote)

![Replacing icons in Keynote is easy!](https://user-images.githubusercontent.com/10384315/54571638-f4132080-49a0-11e9-9e4e-406ce3c44ec1.gif)

| Step | Example |
| --- | --- |
| 1. Open [GitHub-keynote-icons.key](https://primer.github.io/presentations/assets-list.html#marketing-icons) | <img width="500" alt="Screenshot 2019-03-18 13 35 39" src="https://user-images.githubusercontent.com/10384315/54571249-13a94980-499f-11e9-9643-1401534922d4.png"> |
| 2. Select icon and copy | <img width="500" alt="Screenshot 2019-03-18 13 41 25" src="https://user-images.githubusercontent.com/10384315/54570982-f45dec80-499d-11e9-9a40-66f3dda7e1e7.png"> |
| 3. In your presentation, select your icon layout template (1-4 icons available) | <img width="248" alt="Screenshot 2019-03-21 11 51 42" src="https://user-images.githubusercontent.com/10384315/54777536-ba742c80-4bcf-11e9-81e5-df0e518d8ad5.png"> |
| 4. Select the icon you would like to replace | <img width="500" alt="Screenshot 2019-03-18 13 35 00" src="https://user-images.githubusercontent.com/10384315/54570980-f3c55600-499d-11e9-8936-f24830c20413.png"> |
| 5. Paste | <img width="500" alt="Screenshot 2019-03-18 13 43 43" src="https://user-images.githubusercontent.com/10384315/54570983-f45dec80-499d-11e9-9434-07a24f7686d2.png"> |

#### Replace icons (Google Slides)

**Step 1: Choose your icon**
- Go to https://ghicons.github.com/
- Find the icon you’d like to use
- Right click > Copy Image Address

**Step 2: Add to slide**
- On slide, click placeholder icon
- Click Replace Image > By URL
- Paste URL copied from ghicons.github.com

### Illustrations

There is a wide variety of illustrations that are available to use for your presentation. The [Octodex](https://octodex.github.com/) is full of pre-approved Octocat illustrations. If you'd like to customize your own Octocat, use the [Octocat Generator](https://myoctocat.com/).

If you are looking for a specific illustration please contact [@ashygee](https://github.slack.com/team/UDY7XTA79).

## Backgrounds
Background colors should be limited to the colors provided in the template.

<img width="500" alt="Screenshot 2019-03-19 16 30 13" src="https://user-images.githubusercontent.com/10384315/54648634-49fccc80-4a64-11e9-9e86-25ccd1a07870.png">

#### Usage guidelines:

| Don't 🚫 |
| :---: |
| <img width="500" alt="bg-dont-gradient" src="https://user-images.githubusercontent.com/10384315/54648119-40726500-4a62-11e9-95cc-f2798867dfd6.png"> |
| Use gradients or colors outside the provided template. |
| <img width="500" alt="bg-dont-tile" src="https://user-images.githubusercontent.com/10384315/54648132-4d8f5400-4a62-11e9-9445-25016320e1fd.png"> |
| Use tiled images. |

### Background Images

<img width="500" alt="Section Title - Hubot" src="https://user-images.githubusercontent.com/10384315/54648755-b11a8100-4a64-11e9-8e9f-d04cf096224a.png">

Background images should be used _only_ to support, not to distract the viewers. Lower the opacity of a background image to maintain readability.

#### Usage guidelines:

Do ✅ | Don't 🚫
:---: | :---:
 <img width="500" alt="bg-do" src="https://user-images.githubusercontent.com/10384315/54647253-06539400-4a5f-11e9-8315-f14eefee699f.png"> | <img width="500" alt="bg-dont" src="https://user-images.githubusercontent.com/10384315/54647119-a9f07480-4a5e-11e9-93c1-29d6116b8492.png">
Background images should be dimmed to 25% opacity. | Use busy background images when paired with text.




## Slide types
### Quotes
Quotes are set up in two different layouts: left-aligned and centered.

![Screenshot 2019-03-20 13 13 28](https://user-images.githubusercontent.com/10384315/54716005-01035180-4b12-11e9-9194-aa355e4610bf.png)

It is recommended that longer quotes be left-aligned and shorter quotes centered.

### Reactions
![Celebratory reaction](https://user-images.githubusercontent.com/10384315/54715873-ac5fd680-4b11-11e9-9141-cd40c6b24fad.png)

Reaction slides use the GitHub reaction emojis to add a visual cue to a topic.

### Charts
Charts can be easily added to any slide using the built in chart features in both Keynote and Google Slides.

#### Usage guidelines:

Do ✅ | Don't 🚫
:---: | :---:
<img width="957" alt="Screenshot 2019-03-29 17 04 01" src="https://user-images.githubusercontent.com/10384315/55268652-129ed480-5249-11e9-865f-2bcd751bb2ba.png"> | <img width="959" alt="Screenshot 2019-03-29 17 03 36" src="https://user-images.githubusercontent.com/10384315/55268651-12063e00-5249-11e9-82a0-a436be3f2038.png">
Use a white slide for charts with white backgrounds. | Add a chart with a white background to a black slide.


### Charts in Keynote
To add a chart in Keynote click the ![Chart button](https://user-images.githubusercontent.com/10384315/54716264-97377780-4b12-11e9-828f-f006a0679c50.png) button in the top toolbar.

To edit the data in the chart click the chart (if not already selected) and click the `Edit Chart Data` button.
A small spreadsheet window will appear and you can copy/paste your data into the cells.

### Charts in Google Slides
To add a chart in Google slides, click `Insert > Chart` and select the type of chart you would like to use.

If you already have your data in a specific Google Sheet, click `From Sheets...`

To edit the data in the chart, select the chart and click the dropdown arrow in the top right corner. Select `Open Source` and you will be moved to the Google Sheet containing the data for your chart. Within the Sheet, you can update values and customize the appearance of your Chart. To view any of the changes made to your chart and/or it's data, click `Update` to refresh the chart.

# Resources
- [Full assets list](assets-list.md)
- [Keynote template](https://drive.google.com/open?id=1jsWOHJL0hvLfmtQBYL3-srjYhom9z7Ln)
- [Google Slides](https://docs.google.com/presentation/d/1Ex9q_A3-dxWHWw9q2q25KUBmmDkoUMADFKTkVW6o2jw/edit?usp=sharing)
- [Figma file](https://www.figma.com/file/0mXCPvPvDgbtiMEIa5Z8DSh9/Primer-Deck-v1?node-id=0%3A1)

# Versioning
Versioning for the Primer presentation system will be logged by date. All updates will be kept in a changelog located in both the presenters notes of a changelog slide and on the Primer presentations site.
