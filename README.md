# Open Education Resource
This repo will describe specifications for making importable OER content.

##Specs
Content outline title
  - _module-name_ (IE – Lesson 1)
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
    - _Scaffolding_  
      - **Steps-to-completion.md**
        - List of steps to completion
          - Approximate time to complete each item
          - Assignment asset(s) Location: `URL`
            - Visual preview: `Embed code`
        - Assignment submission Location: `URL`
        - In-time information
          - Location: `URL`
      - _Project Assets_
    - **content.md**
      - These are not instructions, rather text and media discourse on a subject matter to generate critical thought.
      - One or any combination of the following:
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
          - In-page viewing: `Embed Code`
          - Transcript Download: `URL`
          - Download Location: `URL`
    - **assessment.md**
      - Style: `diagnostic, formative, summative`
      - Grading-rubric.csv [Using this project](https://github.com/mplewis/csvtomd)
        - Category
          - Category Name: `Text`
          - Due Date: `Y-m-d H:i:s`
          - Total Value: `100`
          - Default feedback: `Text`
          - Custom feebback: `Text`
