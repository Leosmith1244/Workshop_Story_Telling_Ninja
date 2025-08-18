Storytelling Ninja Workshop Website
Overview
This repository hosts the website for the "Become a Storytelling Ninja: Make Them Beg for More" workshop, organized by the PR Pros Toastmasters Club (Club #7903656). The workshop is designed to teach public relations professionals and Toastmasters members how to craft hypnotic stories for speeches, pitches, and more. The site is deployed on Netlify and includes the workshop agenda, speaker outlines, and an explanation of Monroe’s Motivated Sequence with marketing examples. The content is tailored for the online format of the PR Pros Toastmasters Club, held via Zoom in July 2025.
Live Site: [Insert Netlify URL here, e.g., https://storytelling-ninja-workshop.netlify.app]Word of the Day: Hypnotic (adjective) – Producing a compelling or mesmerizing effect.Why Unmissable? You'll weaponize storytelling—for speeches, pitches, and even flirting.
Features

Workshop Agenda: A 90-minute Toastmasters meeting agenda with four 6-minute speeches, interactive activities (3–4 minutes each), and debriefs (3 minutes each), plus Table Topics and club business.
Speaker Outlines: Detailed outlines for four speeches using Monroe’s Motivated Sequence, teaching storytelling techniques like hooks, emotional engagement, plot twists, and improvisation.
Monroe’s Motivated Sequence Guide: An explanation of the persuasive structure, its effectiveness in public relations, and three marketing campaign examples (Nike, Dove, Apple).
Online Optimization: Content designed for Zoom, using chat, breakout rooms, polls, and raise-hand features to engage virtual audiences.
Resources: Links to PR Pros Toastmasters (https://prpros.toastmastersclubs.org/) and FreeToastHost support (https://support.toastmastersclubs.org).

Repository Structure
├── index.html              # Main page with workshop agenda
├── speaker-outlines.html   # Page with speaker outlines
├── monroe-sequence.html    # Page explaining Monroe’s Motivated Sequence
│── styles.css          # Custom styles for the website
├── js/
│   └── scripts.js          # JavaScript for interactivity (e.g., Zoom integration)
├── README.md               # This file
└── netlify.toml            # Netlify configuration file

Setup Instructions
Prerequisites

Node.js: For local development (optional).
Git: To clone and manage the repository.
Netlify CLI: For local testing and deployment (optional).

Installation

Clone the Repository:
git clone https://github.com/[your-username]/storytelling-ninja-workshop.git
cd storytelling-ninja-workshop


Install Dependencies (if using Node.js for local development):
npm install


Run Locally (optional):Use a local server like live-server or http-server:
npm install -g live-server
live-server


Deploy to Netlify:

Connect the repository to Netlify via the Netlify dashboard.
Configure netlify.toml for build settings (e.g., public directory).
Push changes to GitHub to trigger automatic deployment.



Netlify Configuration (netlify.toml)
[build]
  command = "npm run build"  # Adjust if using a build tool
  publish = "public"         # Directory for static files

Usage

Access the Site: Visit the Netlify URL to view the workshop content.
Navigation: Use the menu to access the agenda, speaker outlines, and Monroe’s Motivated Sequence guide.
Interactivity: The site may include links to join PR Pros Toastmasters Zoom meetings or resources for storytelling practice.
Updates: Modify HTML/Markdown files in the repository and push to GitHub for automatic Netlify updates.

Workshop Details

Date: July 2025
Duration: 90 minutes
Format: Online via Zoom
Content:
Speeches: Four 6-minute speeches teaching storytelling techniques (The Hollywood Hook, Emotional Espionage, The Plot Twist Payoff, Improv Storytelling).
Activities: Four interactive activities (3–4 minutes each) using Zoom features (chat, polls, breakout rooms).
Debriefs: Four 3-minute debriefs for participants to share insights.
Toastmasters Elements: Includes Member Introductions, Table Topics, General Evaluation, and Club Business.


Objective: Equip PR professionals and Toastmasters members with storytelling skills for persuasive communication.

Contributing

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Create a pull request for review.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

PR Pros Toastmasters Club: For hosting the workshop (https://prpros.toastmastersclubs.org/).
FreeToastHost: For technical support (https://support.toastmastersclubs.org).
Netlify: For hosting the live site.
Toastmasters International: For providing frameworks like Monroe’s Motivated Sequence.

Contact
For questions or feedback, contact the PR Pros Toastmasters Club via their website or reach out to the repository maintainer at leo.w.smith@gmail.com
