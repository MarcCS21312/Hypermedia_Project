# Hypermedia_Project
Curriculum Vitae Marc Cuesta Sánchez

web-link: https://marccs21312.github.io/Hypermedia_Project/

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

→ User Profile:

  My CV website is mainly designed for the type of users who are looking to hire 3D artists, such as:
  - Human Resources (HR) staff from video game or animation companies.
  - Companies that are looking for technical and artistic profiles.
  - Temporary projects that are looking for someone quickly for a specific and punctual job.

  What these people are looking for is, above all, to see my projects (“Jobs”) in a visual and fast way. They do not have much time to read, so they need to know in a few seconds which tools I use (Blender, Unreal, C#) and 
  if I have the skills they are looking for (both technical skills and soft skills). Therefore, the page must be very clear and visual.
  
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

→ Information Architecture:

  I have decided to make a one-page website because it is visual, lightweight and direct. This way, the user does not have to jump around and wait for different sections to load, or search in different places to see if I 
  meet the requirements.
  
  The structure is efficient. At the top, there is a menu (“header”) that stays fixed (“sticky”). This menu has my name (clickable, which takes you to the “home”) and two main links that lead to “Jobs” (the portfolio) and 
  “Formation” (my studies).
  
  The most important part of the page, the one that is seen first, is divided into two large columns using “flexbox”. In the left column (<div class="cv">) there is my résumé in text: a short introduction, my photo and the 
  list of skills. In the right column ( <div class="portfolio"> ) I have placed the visual portfolio, with images and GIFs of my work.
  
  I have made this decision because this way the recruiter can have both things visible at the same time: they can read what I can do while looking at the visual examples. I think it is the most efficient way to present 
  myself.
  
  Finally, below these two columns, I have added the section “Formation” ( <section id="formation"> ). This section occupies the full width and contains the information about my studies, courses and the languages I speak. I
  have placed it at the end because it is important, but less urgent than the portfolio and the skills.
  
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

→ Visual Design:

  For the design, I wanted a modern style that has a relation with the world of video games or 3D design, that is why I have chosen a “dark mode” (dark theme).

  The background color is a very dark grey, almost black (“#1E1E1E”), and the content blocks (such as the CV card or the training card) are another dark grey (“#1a1a1d”). This makes the atmosphere serious and, most 
  importantly, makes the images and GIFs of the portfolio stand out much more, which in the end is what I want to sell.

  To make it easy to read, the main text is white. But to give it a touch of color and personality, I have used a yellow/gold color (like “#f1e087” or “#b89f60”) for the titles, links and the dividing lines 
  ( <div class="divider"> ).

  An important decision has been the typography. I did not want to use the typical “sans-serif” fonts (like Arial or Roboto) that you see everywhere. I have chosen two “serif” fonts (with serif) that I have imported from 
  Google Fonts: ‘Kaisei Tokumin’ for the normal text and ‘Inria Serif’ for the menu. I think these fonts give a more artistic or “gallery” touch, which fits well with an artist’s portfolio.

  To organize the page I have used “flexbox” (for the main columns and the menu) and “grid” (for the image gallery of the portfolio). I have tried to leave enough space and padding to avoid information overload on the page 
  and therefore speed up the reading.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

→ Link to the Figma Project: 
  
  https://www.figma.com/design/V2vjXElDjhqEwHedfFtGgT/Curriculum?node-id=0-1&m=dev&t=gIksc65R2gvdrzIB-1

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
