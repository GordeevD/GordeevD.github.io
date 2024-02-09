---
layout: essay
type: essay
title: "Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-02-08
published: true
labels:
  - Software Engineering
  - Code Quality
  - Coding Standards
---
<img width="100px" class="rounded float-start pe-4" src="../img/coding-standards/logo.jpg">

## Enforce coding standards
Imagine driving on a highway without lane markings or traffic signals. While navigating solo might be feasible, the presence of others instantly raises the risk and anxiety.
Similarly, coding without standards poses dangers, even if you're the sole author. While seemingly unimportant, 
these "mental barriers" like consistent formatting and naming conventions ensure smooth collaboration and maintainability. 
Just like following traffic rules promotes safety and predictability, coding standards foster:
 1. **Enhanced Readability**: Consistent formats and naming practices make code intuitive, reducing cognitive load for both you and future contributors.
      They become familiar "lanes" everyone navigates effortlessly, minimizing confusion and errors.
 3. **Streamlined Collaboration**: Working on large projects, especially open-source, necessitates shared understanding.
      Standards become a common language, facilitating communication and preventing misinterpretations.
      Imagine contributors merging their code seamlessly, confident it adheres to the team's established "traffic rules."
 5. **Reduced Maintenance**: Well-organized code is easier to debug, update, and extend. By avoiding stylistic idiosyncrasies,
      standards enable smoother handoffs and minimize the time spent deciphering past decisions.
      Think of it as preventive maintenance, keeping your codebase well-paved and free of potholes.
There is many standards exist, and most popular are
[AirBnB Javascript Coding Standards that alligned with ECMAScript](https://github.com/airbnb/javascript)
[Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)
[JavaScript Standard Style](https://github.com/standard/standard)

## Automation to the Rescue
Thankfully, enforcing standards doesn't have to be a tedious chore. 
Enter the world of automated tools like code linters and formatters. 
Tools like ESLint for JavaScript integrate seamlessly with popular IDEs, offering real-time feedback and automatically correcting code on the fly. 
These act as your highway patrol, ensuring everyone adheres to the established coding standards, keeping your codebase "shiny and bright," just like a well-maintained highway.
So, imagine a police in your IDE watching you typing... writing tickets.

## Remember 
Coding standards are not about rigidity, but about building a shared language and a collective framework for creating robust, 
maintainable, and collaborative software. It's like agreeing on traffic signals and lane markings on a vast highway - they don't stifle freedom, 
they enable everyone to navigate efficiently and safely. So, buckle up, embrace the established guidelines, and join the smooth, 
collaborative journey towards successful projects. Remember, the road to great software is paved with consistent, well-understood code, and coding with standards is your trusty GPS on that journey.

*Written by Dmitry Gordeev. Enchanced by Google Gemini*
