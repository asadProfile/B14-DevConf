Prompt:

Create a fully responsive "Latest News" section in HTML and CSS that matches the attached design.

Layout Requirements
Section background: light gray (#f5f5f5).

Centered section heading:

Large bold title: "Latest News"

Small subtitle below: "Stay updated with the latest announcements and updates about DevConf."

Content area uses a 3-column layout on desktop:

Left column: large featured news card.

Middle column: large featured news card.

Right column: vertical list of 3 smaller news items.

Featured News Cards (Left & Center)
Each card should contain:

Large landscape image on top.

News title below image:

Bold.

Around 40px line height.

Two lines of text.

Meta information below title:

Category name.

Bullet separator (•).

Date.

Smaller gray text.

Sidebar News List (Right Column)
Display 3 compact news items stacked vertically:

Small thumbnail image (approximately 100x100).

Content aligned horizontally beside image.

Title in bold.

Meta information underneath:

Category.

Bullet separator.

Date.

Gray text.

Styling
Use modern clean typography.

Max-width container around 1200–1300px.

Equal spacing between columns.

Images should use object-fit: cover.

Smooth hover effect:

Slight image zoom.

Title color transition.

Rounded corners optional but subtle.

Use CSS Grid for desktop layout.

Responsive Behavior
Desktop: 3 columns (2 large cards + sidebar).

Tablet: 2 columns.

Mobile:

All cards stack vertically.

Sidebar items become full-width rows.

Images scale properly.

Code Requirements
Return complete HTML and CSS.

Use semantic HTML5 elements.

No frameworks (Bootstrap, Tailwind, etc.).

Include placeholder images from Unsplash.

Keep code production-ready and well commented.

Structure Example
Latest News
Subtitle

|               |               | Small Item |
| Featured Card | Featured Card | Small Item |
|               |               | Small Item |
