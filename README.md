# Open Education Resource
This repo will describe specifications for making importable OER content.

##Specs
Content outline title
  - module-name.md (IE – Lesson 1)
    - Duration: `Y-m-d H:i:s - Y-m-d H:i:s`
    - **overview.md**
      - Text or video description to get us excited about the topic
    - **learning-objectives.md**
      - Description (Why is this information important)
    - **prerequisite-knowledge-and-skills.md**
      - Does this have prereqs?: `boolean`
      - List items (What do we need to know in order to be successful)
    - **required-materials-or-equipment.md**
      - Are any materials needed?: `boolean`
    - **Steps-to-completion.md**
      - List of steps to completion
        - Approximate time to complete each item
        - Assignment asset(s) Location: `URL`
          - Visual preview: `Embed code`
      - Assignment submission Location: `URL`
      - In-time information
        - Location: `URL`
      - project-assets
    - **content.md**
      - These are not instructions, rather text and media discourse on a subject matter to generate critical thought.
      - Text
        - PDF version: `URL`
        - Citations
        - Fork OER Link: `URL` 
      - Online Resource
        - Location: `URL`
        - Content Downloadable PDF, HTML, etc.
        - Video transcript
      - Textbook Chapter
        - Citation
      - Video
        - Download Location: `URL`
        - Embed Code
        - Transcript: `URL`
    - **assessment.md**
      - Style: `diagnostic, formative, summative`
      - Grading-rubric.csv [Using this project](https://github.com/mplewis/csvtomd)
        - Category
          - Name
          - Due Date
          - Total Value
          - Default feedback
          - Custom feebback
