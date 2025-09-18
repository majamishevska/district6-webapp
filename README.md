# City Councilor Resource App (District 6 – Boston)


**Deployed App:** [www.bostond6.com](https://www.bostond6.com/)  
**Program:** Spark! CDS – Public Interest Technology New England (PIT-NE) Summer Fellowship  
**Role:** Software Engineering Intern (Tech Impact Fellow, Scrum Lead)  

---

## Overview

The **City Councilor Resource App** is a mobile-first, accessible web application designed in partnership with **Boston City Councilor Benjamin J. Weber** (District 6: Jamaica Plain, Roslindale, and West Roxbury). The app centralizes community resources, events, and district initiatives into one platform.

While the City of Boston provides citywide resources, this project addresses the need for **district-specific tools** to help residents access relevant services quickly and allow council staff to maintain up-to-date information.

---

## Key Features

- **Community Resource Directory**
  - Searchable and filterable list by category, keyword, and location (using Nomic for enhanced search)
  - Interactive map with clickable markers showing resource details
  - Submission form for community listings so residents can suggest new local resources

- **Events Calendar**
  - District-specific events managed by council staff
  - Google Calendar integration for easy updates
  - Event posters highlighted on the homepage

- **District Initiatives & Updates**
  - Track projects, policies, and neighborhood developments
  - Archive of newsletters, key links, and government updates

- **Pulse Check (Community Feedback)**
  - Short polls or questions for residents, results filterable by neighborhood
  - Serves as a communication channel between District 6 residents and council staff

- **Admin Dashboard (Strapi CMS)**
  - Add, edit, or remove community resources
  - Manage events, initiatives, staff profiles, and statistics
  - Newsletter signup and distribution tools

- **Accessibility & Language Support**
   Full bilingual functionality (English and Spanish), including search, filters, resource listings, and event details
  - Responsive design across devices

---

## Tech Stack

- **Frontend:** Next.js
- **Backend:** Strapi
- **Storage:** Cloudflare R2 (media, maps, documents)  
- **Other:**  
  - Nomic Embed Text V2 (multilingual semantic search)  
  - Leaflet.js (maps with Google Maps tiles/templates)  
  - Google Calendar API (district + citywide event management)  
  - Accessibility and translation libraries for bilingual support  

---
