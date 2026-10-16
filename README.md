# Hi, I am Andriy 👋

Three projects from automating a school's Moodle LMS (Python, Selenium, REST APIs).
Each project is a standalone repository.

I built them on my own initiative while working in IT support — automating the repetitive manual work around lessons and student progress. They were used in production.

| Project | What it is | Stack |
|---|---|---|
| [`moodle-lesson-pipeline`](https://github.com/Andriy125/moodle-lesson-pipeline) | Google Doc → finished Moodle lesson (HTML, images, H5P, quiz). Resumable, with review gates. | Google Docs API, Selenium, BeautifulSoup/lxml, pytest |
| [`moodle-progress-reports`](https://github.com/Andriy125/moodle-progress-reports) | Async Excel progress report for all students from the Moodle web-service API. | asyncio, httpx, openpyxl, gspread, pytest |
| [`lesson-markup-ai`](https://github.com/Andriy125/lesson-markup-ai) | LLM adds markers to a Google Doc lesson with guard rails: marker-based insert write-back, QA gate, rollback. Pre-step of the pipeline above. | Google Docs API, Claude CLI / Gemini, asyncio, pytest |
