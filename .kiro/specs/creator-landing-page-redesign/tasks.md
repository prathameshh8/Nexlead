# Implementation Plan: Creator Landing Page Redesign

## Overview

This is a simple static HTML/CSS landing page redesign. The focus is on updating the copywriting and content to target YouTube creators instead of roofing agencies. No build tools, no npm, no testing frameworks - just pure HTML/CSS that can be hosted directly on GitHub Pages.

## Tasks

- [x] 1. Set up testing infrastructure and project structure
- [x] 2.1 Update navigation HTML structure
- [x] 2.2 Update navigation CSS styling
- [x] 3.1 Update hero section HTML content
- [x] 3.2 Update hero section CSS styling
- [x] 4.1 Implement founder section HTML structure
- [x] 4.2 Implement founder section CSS styling
- [x] 5.1 Implement pain points HTML structure
- [x] 5.2 Style pain points section
- [x] 6.1 Implement outcomes HTML structure
- [x] 6.2 Style outcomes section

- [x] 7. Update differentiators section
  - Replace "How It Works" section with "WHY NEXSCALE IS DIFFERENT"
  - Add headline: "Most Agencies Haven't Run a Successful Channel. I Have."
  - Add 8 differentiator points covering Algorithm Inversion Framework, founder's success, 80/20 psychology split, low CTR truth, analytics knowledge, experience, topic selection importance, and zero-risk model
  - _Requirements: 6.1-6.8_

- [x] 8. Create misconceptions section
  - Add section label: "THE TRUTH ABOUT VIRAL VIDEOS"
  - Add headline: "Why Everything You've Been Told About Going Viral Is Wrong"
  - Add 5 misconception corrections about CTR, editing quality, topic selection, agency experience, and impression volume
  - Style with comparison or correction format
  - _Requirements: 10.1-10.4_

- [x] 9. Add offer context section
  - Briefly mention 30-day growth sprint
  - Explain Algorithm Inversion Framework
  - Emphasize zero-risk, pay-on-performance model
  - Mention revenue share (20-40% of AdSense) in small text
  - Explain AdSense is smallest income source
  - _Requirements: 13.1-13.5_

- [x] 10. Update final CTA section
  - Update headline: "READY TO START YOUR 30-DAY GROWTH SPRINT?"
  - Update subheadline: "Let's Manufacture Your Next Viral Video—Zero Risk"
  - Add supporting text about Algorithm Inversion Framework
  - Add trust statement: "We only profit when you win. Book a no-pressure discovery call."
  - Keep Calendly widget exactly as-is
  - Add final trust note: "30-day sprint. Pure performance. You win, we win."
  - _Requirements: 5.3, 5.5, 11.1-11.3_

- [x] 11. Update typography to Inter font
  - Replace Google Fonts import with Inter (weights: 400, 500, 600, 700, 800)
  - Update all font-family declarations from Playfair Display/Lora to Inter
  - Verify responsive typography with clamp() is working
  - _Requirements: 12.2, 15.1_

- [x] 12. Add smooth scroll behavior
  - Add simple JavaScript for smooth scrolling to #book-call anchor
  - Test all CTA buttons scroll to Calendly widget
  - _Requirements: 5.4_

- [x] 13. Verify footer links
  - Check Privacy Policy link works (privacy-policy.html)
  - Check Terms and Conditions link works (terms-and-conditions.html)
  - _Requirements: 11.4_

- [x] 14. Final review and cleanup
  - Remove any old roofing agency content
  - Verify all sections flow logically
  - Check all CTAs link to #book-call
  - Verify logo path is correct (Logo/NexScale Logos/n-s.png)
  - Test page in browser (Chrome, Firefox, Safari)
  - Verify mobile responsive behavior
  - _Requirements: All_

## Notes

- This is a static HTML/CSS site - no npm, no build tools, no testing frameworks
- Focus is on copywriting and content updates for YouTube creator audience
- All files can be hosted directly on GitHub Pages
- Keep it simple and clean

