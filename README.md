Try it out over here :

# BITS Premier League 2026

A single-page event landing site for the BITS Premier League (BPL) 2026, organized by the Sports Union Executive Committee at BITS Pilani, Pilani Campus.

BPL is the ultimate sporting showdown at BITS Pilani. This page serves as the central hub for event information, sport-wise registration links, and organizer contact details.

## Features
- Animated dark navy UI with electric blue and cyan accents
- Floating aurora gradient background with glassmorphism cards
- Event dates and form deadlines
- Clickable registration links to Google Forms for 13 sports disciplines:
- Link to the official Event Rules and Regulations (Google Drive folder)
- Contact cards listing Sports Union organizers with phone numbers
- Fully responsive design, works on mobile and desktop
- Clean code architecture with an external stylesheet

## Technologies Used
- HTML5
- Vanilla CSS3 (Custom Properties, Flexbox, CSS Grid)
- Google Fonts (Bebas Neue, Barlow Condensed, Barlow)

## Major Fixes and Improvements: 
--1)Fixed slow redirection to google forms Problem: Earlier after clicking on sport, it took a long time to get redirected to the registration google form. fix: Added dns prefetch and preconnect to google forms domain, so the browser establishes a connection in the background before the user clicks. Forms also now open in a new tab instead of navigating away, which feels significantly faster.
