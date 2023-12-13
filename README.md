Are you ready to begin? Here are this week's Challenge requirements.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes in HTML
Line 7, Changed "website to "Horiseon"

Line 13, changed the "div" element to "header". Line 26 was changed for the closing header.

Line 15, changed "div" tag to "nav" since this is a navigation bar. Line 230 adjusted for closing "nav" tag. 

Line 35's div tag for the "hero" section states "section" 

Line 39's tags changed for "div" to section

Line 41 now has an "id" linking the "search-engine-optimization"

Line 68 "div" changed to "aside"

Line 93 has a "footer" semantics. It closes at line 99.

## Changes in CSS

The benefits, "aside", and sections were cleaned up to run with less code.

The "content" section was cleaned up to run with less code. All the code related to the content section were migrated in css to above the "benefits/aside" section. 



