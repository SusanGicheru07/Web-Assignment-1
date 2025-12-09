### IEEE WIE MMU Website – System User Manual  
(For executive committee, members, and future developers)

#### 1. Overview
This is the official website of **IEEE Women in Engineering (WIE) – Multimedia University of Kenya Student Branch Affinity Group**.  
It serves as the central online presence to showcase activities, leadership, projects, events, gallery, and resources of the Student Bramch Affinity Group.

#### 2. Website Pages & Purpose

| Page            | URL                | Purpose                                                                 |
|-----------------|--------------------|--------------------------------------------------------------------------|
| Home            | index.html         | Welcome page with hero section and “What We Do” summary                  |
| About           | about.html         | History, mission, vision, and objectives of IEEE WIE MMU                 |
| Events          | events.html        | List of past and upcoming events (workshops, outreach, hackathons, etc.) |
| Projects        | projects.html      | Ongoing and completed technical/community projects                       |
| Leadership      | members.html       | Executive committee members with photos, roles, and contacts            |
| Gallery         | gallery.html       | Photo memories from all activities                                       |
| Resources       | resources.html     | Downloadable handbooks, templates, IEEE guides, etc.                     |
| Contact         | contact.html       | Contact form + official email and social media links                     |

#### 3. How to Update Content (For Executives & Web Admin)

Since this is a **static website**:

| Task                            | How to Do It                                                                                 |
|---------------------------------|----------------------------------------------------------------------------------------------|
| Change text (e.g., new event)   | Open the relevant .html file in any text editor and edit the text   |
| Add or replace photos           | Place new image in the images/ folder → update the <img src="images/newphoto.jpg"> path     |
| Add new executive member        | Edit members.html → copy an existing member block and update name, role |
| Update copyright year           | Edit the <footer> in all pages – change 2025 to current year                  |
| Add new page       | Copy an existing HTML file → rename → update title and links in navigation                |

#### 4. File & Folder Structure

```
Root Folder
│
├── index.html
├── about.html
├── events.html
├── projects.html
├── members.html
├── gallery.html
├── resources.html
├── contact.html
├── styles.css            ← All design & colors
├── images/               ← All photos and logo
│     ├── logo.png
│     ├── favicon.ico
│     └── (all event/gallery photos)
```

#### 5. Design Features
- Uses only **HTML5 + CSS** 
- Fast loading – no frameworks used
- Purple & pink brand colors of IEEE WIE
- Accessible (proper headings, alt text on images, abbr for WIE)

