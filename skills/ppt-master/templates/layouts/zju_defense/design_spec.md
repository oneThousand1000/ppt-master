# Academic Defense Template - Design Specification

---

## I. Template Overview

| Property       | Description                                            |
| -------------- | ------------------------------------------------------ |
| **Template Name** | wyq_defense                            |
| **Use Cases**  | Thesis defense, academic presentations, research progress reports, grant applications |
| **Design Tone** | Professional, rigorous, research-oriented, clear hierarchy |
| **Theme Mode** | Light theme (white background + blue title bar)   |

---

## II. Canvas Specification

| Property       | Value                         |
| -------------- | ----------------------------- |
| **Format**     | Standard 16:9                 |
| **Dimensions** | 1280 × 720 px                |
| **viewBox**    | `0 0 1280 720`                |
| **Page Margins** | Left/Right 40px, Top 0px, Bottom 35px |
| **Safe Area**  | x: 40-1240, y: 70-665        |

---

## III. Color Scheme

### Primary Colors

| Role           | Value       | Notes                            |
| -------------- | ----------- | -------------------------------- |
| **Primary Dark Blue** | `#003F88` | Header background, section titles, main headings |
| **Accent Blue** | `#769FCD` | Card borders, icons, secondary decorations |
| **Light Blue-Gray** | `#EEF2F7` | Key message bar background, card inner sections |
| **Background White** | `#FFFFFF` | Page main background           |

### Text Colors

| Role           | Value       | Usage                  |
| -------------- | ----------- | ---------------------- |
| **White Text** | `#FFFFFF`   | Text on dark backgrounds |
| **Primary Text** | `#333333` | Body content           |
| **Secondary Text** | `#666666` | Descriptions, annotations |
| **Muted Gray** | `#999999`  | Footer, auxiliary info |

### Neutral Colors

| Role           | Value       | Usage                  |
| -------------- | ----------- | ---------------------- |
| **Card Gray**  | `#F5F7FA`   | Card inner background, info blocks |
| **Border Gray** | `#D0D7E0`  | Card borders, dividers |

### Functional Colors

| Usage      | Value       | Description    |
| ---------- | ----------- | -------------- |
| **Success** | `#28A745`  | Positive indicators |
| **Warning** | `#FFA500`  | Alerts         |
| **Info**   | `#17A2B8`   | Information tips |

---

## IV. Typography System

### Font Stack

**Font Stack**: `"Microsoft YaHei", "微软雅黑", Arial, sans-serif`

### Font Size Hierarchy

| Level | Usage            | Size | Weight  |
| ----- | ---------------- | ---- | ------- |
| H1    | Cover main title | 56px | Bold    |
| H2    | Page title       | 26px | Bold    |
| H3    | Section title    | 56px | Bold    |
| H4    | Card title       | 16px | Bold    |
| P     | Body content     | 14px | Regular |
| High  | Highlighted data | 36px | Bold    |
| Sub   | Notes/sources    | 14px | Regular |
| XS    | Page number/copyright | 12px | Regular |

---

## VI. Page Types

### 1. Summary Content Page (幻灯片1.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Key message banner: blue arrow-shaped subtitle block followed by a light blue-gray message bar
- Upper content area: large dashed rounded rectangle with bullet marker and flexible content text
- Central key message: emphasized dark blue key message text between upper and lower sections
- Two-card lower layout: left and right dashed containers with rounded light blue-gray content cards
- Card headers: blue title bars with section names
- Footer: light blue bottom bar, page number on the right

### 2. Two-Panel Key Points Page (幻灯片2.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Key message banner: blue arrow-shaped subtitle block followed by a light blue-gray message bar
- Two-panel layout: left and right large rounded rectangular containers
- Panel headers: centered section names above each container
- Number badges: blue rounded-square labels marking each panel
- Flexible content areas: text/image blocks placed inside each panel
- Insight bars: light blue-gray rounded bars with lightbulb icons at the bottom of each panel
- Footer: light blue bottom bar, page number on the right

### 3. Timeline Page (幻灯片3.SVG)

-  White background
-  Top header: section number + page title, with university logos on both sides
-  Subtitle line: section name with bullet point
-  Flexible timeline/process area: numbered circular nodes connected by arrows
-  Highlight nodes: large dark/gray circular icons for start/end milestones
-  Footer: light blue bottom bar, page number on the right

### 4. Quote Page (幻灯片4.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Main quote/content area: large light blue-gray tilted card with subtle border
- Quote mark: dark quotation symbol at the upper-left of the card
- Flexible content area: main text placed inside the quote card
- Footer: light blue bottom bar, page number on the right

### 5. Two-Column Comparison Page (幻灯片5.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Two-column layout: left and right tilted light blue-gray content panels
- Column headers: semi-transparent blue-gray tilted title bars above each panel
- Flexible content areas: separate text/image blocks inside each column
- Footer: light blue bottom bar, page number on the right

### 6. Three-Column Card Page (幻灯片6.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Three-column layout: three vertically aligned light blue-gray cards
- Card headers: section name with large translucent background numbers
- Divider line: dashed horizontal separator between header and body area
- Icon area: centered thematic icon in each card
- Flexible content areas: text/image blocks placed inside each card
- Footer: light blue bottom bar, page number on the right

### 7. Four-Column Vertical Label Page (幻灯片7.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Four-column layout: four tilted light blue-gray content panels
- Vertical labels: section name displayed vertically on the left side of each panel
- Label decoration: semi-transparent blue-gray vertical title bars behind each label
- Flexible content areas: text/image blocks placed inside each panel
- Footer: light blue bottom bar, page number on the right

### 8. Circular Process Page (幻灯片8.SVG)

- Patterned white background with subtle repeated emblem texture
- Top header: section number + page title, with university logos on both sides
- Central process diagram: four colored circular icon nodes arranged around a dotted circle
- Center decoration: large semi-transparent abstract emblem behind the process diagram
- Four supporting text areas: section name + content text placed around the diagram
- Footer: light blue bottom bar, page number on the right

### 9. Horizontal Timeline Page (幻灯片9.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Central horizontal timeline: connected line with five milestone nodes
- Milestone icons: colored hexagonal icon badges placed above the timeline
- Date labels: milestone dates positioned above each icon
- Alternating content areas: section name + content text placed above/below the timeline
- Connector lines: vertical lines linking each milestone icon to the timeline
- Footer: light blue bottom bar, page number on the right

### 10. Process Arrow Page (幻灯片10.SVG)

- Patterned white background with subtle repeated emblem texture
- Top header: section number + page title, with university logos on both sides
- Subtitle line: section name with bullet point
- Central process flow: five connected colored arrow blocks arranged horizontally
- Step labels: content text placed inside each arrow block
- Annotation markers: small colored triangle pointers above/below the process flow
- Supporting text areas: content text placed around the flow to explain each step
- Center decoration: large semi-transparent abstract emblem behind the process flow
- Footer: light blue bottom bar, page number on the right

### 11. Bar Chart Page (幻灯片11.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Subtitle line: chart type or section name with bullet point
- Main chart area: large light blue-gray tilted card with subtle border
- Bar chart layout: monthly grouped bars with axis labels and grid lines
- Supporting content area: text annotation placed on the right side of the chart card
- Data source note: bold data source description at the lower-left
- Footer: light blue bottom bar, page number on the right

### 12. Horizontal Bar Chart Page (幻灯片12.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Subtitle line: chart type or section name with bullet point
- Main chart area: large light blue-gray tilted card with subtle border
- Horizontal bar chart layout: monthly stacked bars with axis labels and grid lines
- Supporting content area: text annotation placed on the right side of the chart card
- Data source note: bold data source description at the lower-left
- Footer: light blue bottom bar, page number on the right

### 13. Image Showcase Page (幻灯片13.SVG)

- White background
- Top header: section number + page title, with university logos on both sides
- Subtitle line: content type or section name with bullet point
- Two-column layout: text summary on the left, large visual display on the right
- Main image area: large monitor mockup containing the featured image
- Key message area: highlighted red key message text below the description
- Icon indicators: three circular icon badges placed at the lower-left
- Footer: light blue bottom bar, page number on the right













---

## VII. Layout Patterns

| Pattern            | Use Cases                      |
| ------------------ | ------------------------------ |
| **Single Column Centered** | Cover, ending, key points |
| **Two-Column Cards** | Table of contents            |
| **Left-Right Split (5:5)** | Comparison display or Image-text mixed layout |
| **Left-Right Split (4:6)** | Image-text mixed layout |
| **Card Grid**      | Research content list           |
| **Timeline**       | Pipeline     |
| **Table**          | Data comparison, experiment results |

---

## VIII. Spacing Guidelines

| Element            | Value  |
| ------------------ | ------ |
| Card gap           | 20px   |
| Content block gap  | 24px   |
| Card padding       | 20px   |
| Card border radius | 8px    |
| Icon-to-text gap   | 12px   |

---

## IX. SVG Technical Constraints

### Mandatory Rules

1. viewBox: `0 0 1280 720`
2. Use `<rect>` elements for backgrounds
3. Use `<tspan>` for text wrapping (no `<foreignObject>`)
4. Use `fill-opacity` / `stroke-opacity` for transparency; no `rgba()`
5. Prohibited: `mask`, `<style>`, `class`, `foreignObject`. `clipPath` is allowed only on `<image>` under `shared-standards.md` §1.2
6. Prohibited: `textPath`, `animate*`, `script`
7. `marker-start` / `marker-end` conditionally allowed (marker in `<defs>`, `orient="auto"`, shape = triangle/diamond/oval) — see shared-standards.md §1.1

### PPT Compatibility Rules

- No `<g opacity="...">` (group opacity); set opacity on each child element individually
- Use overlay layers for image transparency
- Inline styles only; no external CSS or `@font-face`

---

## X. Placeholder Specification

Templates use `{{PLACEHOLDER}}` format placeholders. Common placeholders:

| Placeholder        | Description        |
| ------------------ | ------------------ |
| `{{TITLE}}`        | Thesis/project main title |
| `{{SUBTITLE}}`     | Subtitle           |
| `{{AUTHOR}}`       | Presenter name     |
| `{{ADVISOR}}`      | Advisor            |
| `{{INSTITUTION}}`  | University/institution |
| `{{DATE}}`         | Defense date       |
| `{{PAGE_TITLE}}`   | Page title         |
| `{{SECTION_NUM}}`  | Section number     |
| `{{CHAPTER_NUM}}`  | Chapter number (large) |
| `{{CHAPTER_TITLE}}`| Chapter title      |
| `{{CHAPTER_DESC}}` | Chapter description |
| `{{KEY_MESSAGE}}`  | Key message        |
| `{{PAGE_NUM}}`     | Page number        |
| `{{SOURCE}}`       | Data source        |
| `{{SECTION_NAME}}` | Section name (footer) |
| `{{TOC_ITEM_N_TITLE}}` | TOC item title (N=1..n) |
| `{{TOC_ITEM_N_DESC}}` | TOC item description (N=1..n) |
| `{{THANK_YOU}}`    | Thank-you message  |
| `{{ENDING_SUBTITLE}}` | Ending subtitle/tagline |
| `{{CONTACT_INFO}}` | Contact information |
| `{{EMAIL}}`        | Email address      |
| `{{COPYRIGHT}}`    | Copyright info     |
| `{{LOGO}}`         | Logo text          |

---

## XI. Component Specifications

### 1. Summary Content Page (幻灯片1.SVG)

Main Title

```xml
<!-- Large centered main title -->
<text x="960" y="310" text-anchor="middle" fill="#000000" font-size="52" font-weight="bold">
  {{PAGE_TITLE}}
</text>
```

Subtitle

```xml
<!-- Centered subtitle below main title -->
<text x="960" y="385" text-anchor="middle" fill="#333333" font-size="28" font-weight="normal">
  {{SUBTITLE}}
</text>
```



### 2. Two-Panel Key Points Page (幻灯片2.SVG)

Key Message Banner

```xml
<!-- Blue arrow-shaped subtitle block + light blue-gray message bar -->
<polygon points="70,120 380,120 420,160 380,200 70,200" fill="#6F9FD0" stroke="#FFFFFF" stroke-width="2"/>
<rect x="420" y="120" width="1320" height="80" fill="#DCE8F2"/>
<text x="225" y="168" text-anchor="middle" fill="#FFFFFF" font-size="26" font-weight="bold">{{SUBTITLE}}</text>
<text x="450" y="168" fill="#000000" font-size="28">{{KEY_MESSAGE}}</text>
```

Two-Panel Containers

```xml
<!-- Left and right rounded outline containers -->
<rect x="75" y="250" width="860" height="650" fill="none" stroke="#6F9FD0" stroke-width="2" rx="28"/>
<rect x="970" y="250" width="860" height="650" fill="none" stroke="#6F9FD0" stroke-width="2" rx="28"/>
```

Number Badge

```xml
<!-- Blue rounded-square number badge -->
<rect x="105" y="285" width="65" height="65" fill="#4F88C6" rx="8"/>
<text x="137.5" y="328" text-anchor="middle" fill="#FFFFFF" font-size="32" font-weight="bold">1</text>
```

Insight Bar

```xml
<!-- Light blue-gray rounded insight bar with icon area -->
<rect x="100" y="785" width="810" height="90" fill="#EDF3F8" rx="22"/>
<text x="135" y="845" fill="#4F88C6" font-size="42">💡</text>
```

### 3. Timeline Page (幻灯片3.SVG)

Timeline Nodes

```xml
<!-- Numbered circular timeline nodes -->
<circle cx="260" cy="520" r="42" fill="#6F9FD0"/>
<text x="260" y="532" text-anchor="middle" fill="#FFFFFF" font-size="30" font-weight="bold">1</text>

<circle cx="560" cy="520" r="42" fill="#6F9FD0"/>
<text x="560" y="532" text-anchor="middle" fill="#FFFFFF" font-size="30" font-weight="bold">2</text>
```

Flow Arrows

```xml
<!-- Horizontal arrows connecting timeline nodes -->
<line x1="310" y1="520" x2="510" y2="520" stroke="#6F9FD0" stroke-width="3"/>
<polygon points="510,512 528,520 510,528" fill="#6F9FD0"/>
```

Milestone Highlight Node

```xml
<!-- Large dark milestone node for start/end highlight -->
<circle cx="135" cy="520" r="58" fill="#3E4E63"/>
<text x="135" y="532" text-anchor="middle" fill="#FFFFFF" font-size="28" font-weight="bold">{{START}}</text>
```

Timeline Text Block

```xml
<!-- Text block below each timeline node -->
<text x="260" y="610" text-anchor="middle" fill="#1F2D3D" font-size="22" font-weight="bold">{{STEP_TITLE}}</text>
<text x="260" y="645" text-anchor="middle" fill="#666666" font-size="16">{{STEP_DESCRIPTION}}</text>
```

### 4. Quote Page (幻灯片4.SVG)

Quote Card

```xml
<!-- Large tilted light blue-gray quote card with subtle border -->
<g transform="rotate(-3 960 520)">
  <rect x="260" y="250" width="1400" height="520" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="18"/>
</g>
```

Main Quote Text

```xml
<!-- Centered main quote text inside the card -->
<text x="960" y="480" text-anchor="middle" fill="#1F2D3D" font-size="32" font-weight="bold">
  {{QUOTE_TEXT}}
</text>
<text x="960" y="535" text-anchor="middle" fill="#4A4A4A" font-size="22">
  {{QUOTE_DESCRIPTION}}
</text>
```

Quote Source

```xml
<!-- Optional source or author text below the quote -->
<text x="960" y="650" text-anchor="middle" fill="#666666" font-size="18">
  —— {{QUOTE_SOURCE}}
</text>
```

### 5. Two-Column Comparison Page (幻灯片5.SVG)

Two-Column Content Panels

```xml
<!-- Left and right tilted light blue-gray content panels -->
<g transform="rotate(-2 520 560)">
  <rect x="150" y="260" width="720" height="560" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="16"/>
</g>
<g transform="rotate(2 1400 560)">
  <rect x="1050" y="260" width="720" height="560" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="16"/>
</g>
```

Column Header Bars

```xml
<!-- Tilted semi-transparent blue-gray title bars above each panel -->
<g transform="rotate(-2 520 245)">
  <rect x="220" y="205" width="600" height="70" fill="#BFD0DF" opacity="0.85" rx="10"/>
  <text x="520" y="250" text-anchor="middle" fill="#1F2D3D" font-size="26" font-weight="bold">{{LEFT_TITLE}}</text>
</g>
<g transform="rotate(2 1400 245)">
  <rect x="1120" y="205" width="600" height="70" fill="#BFD0DF" opacity="0.85" rx="10"/>
  <text x="1420" y="250" text-anchor="middle" fill="#1F2D3D" font-size="26" font-weight="bold">{{RIGHT_TITLE}}</text>
</g>
```

Flexible Content Blocks

```xml
<!-- Text or image placeholders inside each column panel -->
<rect x="220" y="330" width="580" height="420" fill="#FFFFFF" opacity="0.85" rx="10"/>
<text x="510" y="555" text-anchor="middle" fill="#666666" font-size="22">{{LEFT_CONTENT}}</text>

<rect x="1120" y="330" width="580" height="420" fill="#FFFFFF" opacity="0.85" rx="10"/>
<text x="1410" y="555" text-anchor="middle" fill="#666666" font-size="22">{{RIGHT_CONTENT}}</text>
```

### 6. Three-Column Card Page (幻灯片6.SVG)

Three-Column Card Containers

```xml
<!-- Three vertically aligned light blue-gray content cards -->
<rect x="120" y="250" width="500" height="620" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="18"/>
<rect x="710" y="250" width="500" height="620" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="18"/>
<rect x="1300" y="250" width="500" height="620" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="18"/>
```

Card Header with Background Number

```xml
<!-- Card header with large translucent background number -->
<text x="160" y="365" fill="#BFD0DF" font-size="120" font-weight="bold" opacity="0.55">01</text>
<text x="250" y="330" fill="#1F2D3D" font-size="26" font-weight="bold">{{CARD_TITLE}}</text>
```

Dashed Divider Line

```xml
<!-- Dashed horizontal separator between header and body area -->
<line x1="160" y1="390" x2="580" y2="390" stroke="#6F9FD0" stroke-width="2" stroke-dasharray="8 8"/>
```

Icon Area

```xml
<!-- Centered thematic icon inside each card -->
<circle cx="370" cy="540" r="70" fill="#DDEAF5"/>
<text x="370" y="565" text-anchor="middle" fill="#3E4E63" font-size="54">{{ICON}}</text>
```

Flexible Content Area

```xml
<!-- Text or image placeholder inside the card body -->
<rect x="170" y="650" width="400" height="150" fill="#FFFFFF" opacity="0.85" rx="10"/>
<text x="370" y="735" text-anchor="middle" fill="#666666" font-size="20">{{CONTENT}}</text>
```

### 7. Four-Column Vertical Label Page (幻灯片7.SVG)

Four-Column Tilted Panels

```xml
<!-- Four tilted light blue-gray vertical content panels -->
<g transform="rotate(-2 300 560)">
  <rect x="120" y="260" width="330" height="600" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="16"/>
</g>
<g transform="rotate(2 730 560)">
  <rect x="550" y="260" width="330" height="600" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="16"/>
</g>
<g transform="rotate(-2 1160 560)">
  <rect x="980" y="260" width="330" height="600" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="16"/>
</g>
<g transform="rotate(2 1590 560)">
  <rect x="1410" y="260" width="330" height="600" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="16"/>
</g>
```

Vertical Label Bars

```xml
<!-- Semi-transparent vertical title bars behind each label -->
<rect x="100" y="300" width="55" height="500" fill="#BFD0DF" opacity="0.85" rx="8"/>
<rect x="530" y="300" width="55" height="500" fill="#BFD0DF" opacity="0.85" rx="8"/>
<rect x="960" y="300" width="55" height="500" fill="#BFD0DF" opacity="0.85" rx="8"/>
<rect x="1390" y="300" width="55" height="500" fill="#BFD0DF" opacity="0.85" rx="8"/>
```

Vertical Label Text

```xml
<!-- Section names displayed vertically on the left side of each panel -->
<text x="128" y="550" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold" writing-mode="tb">
  {{LABEL}}
</text>
```

Flexible Content Blocks

```xml
<!-- Text or image placeholders inside each vertical panel -->
<rect x="180" y="330" width="230" height="460" fill="#FFFFFF" opacity="0.85" rx="10"/>
<text x="295" y="570" text-anchor="middle" fill="#666666" font-size="18">{{CONTENT}}</text>
```

### 8. Circular Process Page (幻灯片8.SVG)

Circular Process Diagram

```xml
<!-- Four colored circular icon nodes arranged around a dotted circle -->
<circle cx="960" cy="520" r="250" fill="none" stroke="#B8C9D8" stroke-width="3" stroke-dasharray="8 10"/>

<circle cx="960" cy="270" r="58" fill="#6F9FD0"/>
<text x="960" y="290" text-anchor="middle" fill="#FFFFFF" font-size="46">{{ICON_1}}</text>

<circle cx="1210" cy="520" r="58" fill="#CC6666"/>
<text x="1210" y="540" text-anchor="middle" fill="#FFFFFF" font-size="46">{{ICON_2}}</text>

<circle cx="960" cy="770" r="58" fill="#6F9FD0"/>
<text x="960" y="790" text-anchor="middle" fill="#FFFFFF" font-size="46">{{ICON_3}}</text>

<circle cx="710" cy="520" r="58" fill="#CC6666"/>
<text x="710" y="540" text-anchor="middle" fill="#FFFFFF" font-size="46">{{ICON_4}}</text>
```

Central Background Emblem

```xml
<!-- Large semi-transparent abstract emblem behind the process diagram -->
<text x="960" y="610" text-anchor="middle" fill="#DDEAF5" font-size="360" font-weight="bold" opacity="0.35">
  {{EMBLEM}}
</text>
```

Supporting Text Areas

```xml
<!-- Four supporting text blocks around the circular diagram -->
<text x="430" y="310" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold">{{TITLE_1}}</text>
<text x="430" y="350" text-anchor="middle" fill="#666666" font-size="17">{{CONTENT_1}}</text>

<text x="1490" y="310" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold">{{TITLE_2}}</text>
<text x="1490" y="350" text-anchor="middle" fill="#666666" font-size="17">{{CONTENT_2}}</text>

<text x="430" y="755" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold">{{TITLE_3}}</text>
<text x="430" y="795" text-anchor="middle" fill="#666666" font-size="17">{{CONTENT_3}}</text>

<text x="1490" y="755" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold">{{TITLE_4}}</text>
<text x="1490" y="795" text-anchor="middle" fill="#666666" font-size="17">{{CONTENT_4}}</text>
```

### 9. Horizontal Timeline Page (幻灯片9.SVG)

Horizontal Timeline Line

```xml
<!-- Central horizontal timeline line -->
<line x1="220" y1="540" x2="1700" y2="540" stroke="#6F9FD0" stroke-width="4"/>
```

Milestone Nodes

```xml
<!-- Five milestone nodes placed along the timeline -->
<circle cx="300" cy="540" r="13" fill="#6F9FD0"/>
<circle cx="640" cy="540" r="13" fill="#6F9FD0"/>
<circle cx="960" cy="540" r="13" fill="#6F9FD0"/>
<circle cx="1280" cy="540" r="13" fill="#6F9FD0"/>
<circle cx="1620" cy="540" r="13" fill="#6F9FD0"/>
```

Milestone Icon Badges

```xml
<!-- Colored hexagonal icon badges above the timeline -->
<polygon points="300,330 355,365 355,435 300,470 245,435 245,365" fill="#6F9FD0"/>
<text x="300" y="420" text-anchor="middle" fill="#FFFFFF" font-size="46">{{ICON_1}}</text>

<polygon points="640,330 695,365 695,435 640,470 585,435 585,365" fill="#CC6666"/>
<text x="640" y="420" text-anchor="middle" fill="#FFFFFF" font-size="46">{{ICON_2}}</text>
```

Date Labels

```xml
<!-- Date labels placed above milestone icon badges -->
<text x="300" y="300" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold">{{DATE_1}}</text>
<text x="640" y="300" text-anchor="middle" fill="#1F2D3D" font-size="24" font-weight="bold">{{DATE_2}}</text>
```

Vertical Connectors

```xml
<!-- Vertical connector lines linking icons to the timeline -->
<line x1="300" y1="470" x2="300" y2="527" stroke="#6F9FD0" stroke-width="3"/>
<line x1="640" y1="470" x2="640" y2="527" stroke="#CC6666" stroke-width="3"/>
```

Alternating Content Blocks

```xml
<!-- Content text placed above and below the central timeline -->
<text x="300" y="620" text-anchor="middle" fill="#1F2D3D" font-size="22" font-weight="bold">{{TITLE_1}}</text>
<text x="300" y="660" text-anchor="middle" fill="#666666" font-size="16">{{CONTENT_1}}</text>

<text x="640" y="215" text-anchor="middle" fill="#1F2D3D" font-size="22" font-weight="bold">{{TITLE_2}}</text>
<text x="640" y="255" text-anchor="middle" fill="#666666" font-size="16">{{CONTENT_2}}</text>
```

### 10. Process Arrow Page (幻灯片10.SVG)

Process Arrow Blocks

```xml
<!-- Five connected colored arrow blocks arranged horizontally -->
<polygon points="170,430 430,430 470,500 430,570 170,570 210,500" fill="#6F9FD0"/>
<polygon points="450,430 710,430 750,500 710,570 450,570 490,500" fill="#CC6666"/>
<polygon points="730,430 990,430 1030,500 990,570 730,570 770,500" fill="#6F9FD0"/>
<polygon points="1010,430 1270,430 1310,500 1270,570 1010,570 1050,500" fill="#CC6666"/>
<polygon points="1290,430 1550,430 1590,500 1550,570 1290,570 1330,500" fill="#6F9FD0"/>
```

Step Labels

```xml
<!-- Centered text labels inside each arrow block -->
<text x="320" y="510" text-anchor="middle" fill="#FFFFFF" font-size="24" font-weight="bold">{{STEP_1}}</text>
<text x="600" y="510" text-anchor="middle" fill="#FFFFFF" font-size="24" font-weight="bold">{{STEP_2}}</text>
<text x="880" y="510" text-anchor="middle" fill="#FFFFFF" font-size="24" font-weight="bold">{{STEP_3}}</text>
<text x="1160" y="510" text-anchor="middle" fill="#FFFFFF" font-size="24" font-weight="bold">{{STEP_4}}</text>
<text x="1440" y="510" text-anchor="middle" fill="#FFFFFF" font-size="24" font-weight="bold">{{STEP_5}}</text>
```

Annotation Markers

```xml
<!-- Small colored triangle pointers above and below the process flow -->
<polygon points="320,390 305,415 335,415" fill="#6F9FD0"/>
<polygon points="600,610 585,585 615,585" fill="#CC6666"/>
<polygon points="880,390 865,415 895,415" fill="#6F9FD0"/>
```

Supporting Text Blocks

```xml
<!-- Explanatory text blocks placed around the process arrows -->
<text x="320" y="350" text-anchor="middle" fill="#1F2D3D" font-size="22" font-weight="bold">{{TITLE_1}}</text>
<text x="320" y="382" text-anchor="middle" fill="#666666" font-size="16">{{CONTENT_1}}</text>

<text x="600" y="680" text-anchor="middle" fill="#1F2D3D" font-size="22" font-weight="bold">{{TITLE_2}}</text>
<text x="600" y="712" text-anchor="middle" fill="#666666" font-size="16">{{CONTENT_2}}</text>
```

Central Background Emblem

```xml
<!-- Large semi-transparent abstract emblem behind the process flow -->
<text x="960" y="650" text-anchor="middle" fill="#DDEAF5" font-size="340" font-weight="bold" opacity="0.35">
  {{EMBLEM}}
</text>
```

### 11. Bar Chart Page (幻灯片11.SVG)

Main Chart Card

```xml
<!-- Large tilted light blue-gray chart card with subtle border -->
<g transform="rotate(-2 960 540)">
  <rect x="180" y="240" width="1500" height="620" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="18"/>
</g>
```

Bar Chart Axes

```xml
<!-- Chart axes with light grid lines -->
<line x1="300" y1="720" x2="1180" y2="720" stroke="#3E4E63" stroke-width="2"/>
<line x1="300" y1="330" x2="300" y2="720" stroke="#3E4E63" stroke-width="2"/>

<line x1="300" y1="640" x2="1180" y2="640" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
<line x1="300" y1="560" x2="1180" y2="560" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
<line x1="300" y1="480" x2="1180" y2="480" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
<line x1="300" y1="400" x2="1180" y2="400" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
```

Grouped Bar Elements

```xml
<!-- Monthly grouped bars in blue and red -->
<rect x="360" y="560" width="38" height="160" fill="#6F9FD0" rx="4"/>
<rect x="405" y="500" width="38" height="220" fill="#CC6666" rx="4"/>

<rect x="520" y="480" width="38" height="240" fill="#6F9FD0" rx="4"/>
<rect x="565" y="430" width="38" height="290" fill="#CC6666" rx="4"/>

<rect x="680" y="520" width="38" height="200" fill="#6F9FD0" rx="4"/>
<rect x="725" y="450" width="38" height="270" fill="#CC6666" rx="4"/>
```

Axis Labels

```xml
<!-- Month labels and value labels for the bar chart -->
<text x="400" y="760" text-anchor="middle" fill="#666666" font-size="16">{{MONTH_1}}</text>
<text x="560" y="760" text-anchor="middle" fill="#666666" font-size="16">{{MONTH_2}}</text>
<text x="720" y="760" text-anchor="middle" fill="#666666" font-size="16">{{MONTH_3}}</text>

<text x="270" y="725" text-anchor="end" fill="#666666" font-size="14">0</text>
<text x="270" y="645" text-anchor="end" fill="#666666" font-size="14">25</text>
<text x="270" y="565" text-anchor="end" fill="#666666" font-size="14">50</text>
<text x="270" y="485" text-anchor="end" fill="#666666" font-size="14">75</text>
<text x="270" y="405" text-anchor="end" fill="#666666" font-size="14">100</text>
```

Legend

```xml
<!-- Chart legend with blue and red series markers -->
<rect x="330" y="280" width="22" height="22" fill="#6F9FD0" rx="3"/>
<text x="365" y="298" fill="#1F2D3D" font-size="16">{{SERIES_A}}</text>

<rect x="500" y="280" width="22" height="22" fill="#CC6666" rx="3"/>
<text x="535" y="298" fill="#1F2D3D" font-size="16">{{SERIES_B}}</text>
```

Right Annotation Area

```xml
<!-- Supporting text annotation placed on the right side of the chart card -->
<text x="1320" y="390" text-anchor="middle" fill="#1F2D3D" font-size="26" font-weight="bold">{{ANNOTATION_TITLE}}</text>
<text x="1320" y="440" text-anchor="middle" fill="#666666" font-size="18">{{ANNOTATION_TEXT}}</text>
```

Data Source Note

```xml
<!-- Bold data source note at the lower-left of the chart card -->
<text x="240" y="825" fill="#1F2D3D" font-size="18" font-weight="bold">
  {{DATA_SOURCE}}
</text>
```

### 12. Horizontal Bar Chart Page (幻灯片12.SVG)

Main Chart Card

```xml
<!-- Large tilted light blue-gray chart card with subtle border -->
<g transform="rotate(-2 960 540)">
  <rect x="180" y="240" width="1500" height="620" fill="#EAF1F7" stroke="#B8C9D8" stroke-width="2" rx="18"/>
</g>
```

Horizontal Bar Chart Axes

```xml
<!-- Horizontal chart axes with light vertical grid lines -->
<line x1="360" y1="760" x2="1220" y2="760" stroke="#3E4E63" stroke-width="2"/>
<line x1="360" y1="340" x2="360" y2="760" stroke="#3E4E63" stroke-width="2"/>

<line x1="520" y1="340" x2="520" y2="760" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
<line x1="680" y1="340" x2="680" y2="760" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
<line x1="840" y1="340" x2="840" y2="760" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
<line x1="1000" y1="340" x2="1000" y2="760" stroke="#B8C9D8" stroke-width="1" stroke-dasharray="6 6"/>
```

Stacked Horizontal Bars

```xml
<!-- Monthly stacked horizontal bars in blue and red -->
<rect x="360" y="390" width="300" height="34" fill="#6F9FD0" rx="4"/>
<rect x="660" y="390" width="180" height="34" fill="#CC6666" rx="4"/>

<rect x="360" y="490" width="420" height="34" fill="#6F9FD0" rx="4"/>
<rect x="780" y="490" width="220" height="34" fill="#CC6666" rx="4"/>

<rect x="360" y="590" width="360" height="34" fill="#6F9FD0" rx="4"/>
<rect x="720" y="590" width="260" height="34" fill="#CC6666" rx="4"/>
```

Axis Labels

```xml
<!-- Month labels and value labels for the horizontal bar chart -->
<text x="330" y="414" text-anchor="end" fill="#666666" font-size="16">{{MONTH_1}}</text>
<text x="330" y="514" text-anchor="end" fill="#666666" font-size="16">{{MONTH_2}}</text>
<text x="330" y="614" text-anchor="end" fill="#666666" font-size="16">{{MONTH_3}}</text>

<text x="360" y="795" text-anchor="middle" fill="#666666" font-size="14">0</text>
<text x="520" y="795" text-anchor="middle" fill="#666666" font-size="14">25</text>
<text x="680" y="795" text-anchor="middle" fill="#666666" font-size="14">50</text>
<text x="840" y="795" text-anchor="middle" fill="#666666" font-size="14">75</text>
<text x="1000" y="795" text-anchor="middle" fill="#666666" font-size="14">100</text>
```

Legend

```xml
<!-- Chart legend with blue and red series markers -->
<rect x="390" y="290" width="22" height="22" fill="#6F9FD0" rx="3"/>
<text x="425" y="308" fill="#1F2D3D" font-size="16">{{SERIES_A}}</text>

<rect x="560" y="290" width="22" height="22" fill="#CC6666" rx="3"/>
<text x="595" y="308" fill="#1F2D3D" font-size="16">{{SERIES_B}}</text>
```

Right Annotation Area

```xml
<!-- Supporting text annotation placed on the right side of the chart card -->
<text x="1350" y="410" text-anchor="middle" fill="#1F2D3D" font-size="26" font-weight="bold">{{ANNOTATION_TITLE}}</text>
<text x="1350" y="460" text-anchor="middle" fill="#666666" font-size="18">{{ANNOTATION_TEXT}}</text>
```

Data Source Note

```xml
<!-- Bold data source note at the lower-left of the chart card -->
<text x="240" y="825" fill="#1F2D3D" font-size="18" font-weight="bold">
  {{DATA_SOURCE}}
</text>
```

### 13. Image Showcase Page (幻灯片13.SVG)

Left Text Summary Area

```xml
<!-- Left-side title and description text block -->
<text x="130" y="310" fill="#1F2D3D" font-size="34" font-weight="bold">{{SUMMARY_TITLE}}</text>
<text x="130" y="365" fill="#666666" font-size="20">{{SUMMARY_TEXT_LINE_1}}</text>
<text x="130" y="400" fill="#666666" font-size="20">{{SUMMARY_TEXT_LINE_2}}</text>
<text x="130" y="435" fill="#666666" font-size="20">{{SUMMARY_TEXT_LINE_3}}</text>
```

Key Message Text

```xml
<!-- Highlighted red key message below the description -->
<text x="130" y="540" fill="#CC0000" font-size="28" font-weight="bold">{{KEY_MESSAGE}}</text>
<text x="130" y="580" fill="#CC0000" font-size="22">{{KEY_MESSAGE_DETAIL}}</text>
```

Icon Indicators

```xml
<!-- Three circular icon badges at the lower-left -->
<circle cx="170" cy="735" r="42" fill="#6F9FD0"/>
<text x="170" y="752" text-anchor="middle" fill="#FFFFFF" font-size="34">{{ICON_1}}</text>

<circle cx="290" cy="735" r="42" fill="#CC6666"/>
<text x="290" y="752" text-anchor="middle" fill="#FFFFFF" font-size="34">{{ICON_2}}</text>

<circle cx="410" cy="735" r="42" fill="#6F9FD0"/>
<text x="410" y="752" text-anchor="middle" fill="#FFFFFF" font-size="34">{{ICON_3}}</text>
```

Monitor Mockup

```xml
<!-- Large monitor-style image frame on the right -->
<rect x="760" y="260" width="920" height="520" fill="#1F2D3D" rx="24"/>
<rect x="795" y="295" width="850" height="450" fill="#FFFFFF" rx="10"/>
<image x="815" y="315" width="810" height="410" href="{{SHOWCASE_IMAGE}}"/>
```

Monitor Stand

```xml
<!-- Simple monitor stand below the image frame -->
<rect x="1130" y="780" width="180" height="35" fill="#3E4E63" rx="6"/>
<polygon points="1190,780 1250,780 1285,850 1155,850" fill="#3E4E63"/>
<rect x="1100" y="850" width="240" height="24" fill="#3E4E63" rx="8"/>
```



## XII. Usage Instructions

1. Copy the template to the project directory
2. Select the appropriate page template based on defense content needs
3. Use placeholders to mark content that needs replacement
4. Ensure presenter info and advisor info are complete
5. Generate the final SVG through the Executor role
