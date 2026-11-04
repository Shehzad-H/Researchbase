## What is ResearchBase?

ResearchBase is a web platform that helps users discover scientific papers, find relevant research, and eventually use AI to understand and compare scientific findings.

The problem: Researchers and students often spend significant time searching through papers to find information relevant to a specific question.

Our solution: A search engine that organizes research papers and returns relevant results with useful metadata and links to original sources.

## Target Users

prioritizing:
- University students conducting literature reviews.
- Undergraduate and graduate researchers looking for related studies.
- Engineers and technical professionals researching scientific subjects.

## Minimum Viable Product

-Research search bar Enter a topic or research question.

-Real paper results Retrieve scientific papers through an external research **API**.

-Paper information Show title, authors, year, journal and abstract when available.

-Research filters Filter by publication year and sort by relevance or date.  -Original source links Open the paper through its **DOI**, publisher or available full-text link.

-Python data pipeline Collect, validate, normalize and store paper metadata.

-Basic automated testing Check that data ingestion and search functions work correctly.

## List of Wins

v0.1 goals:
- A user can enter a research topic.
- The system retrieves actual research papers.
- Search results contain accurate, usable metadata.
- Users can follow links to original papers.
- The Python backend validates data and handles errors.
- Automated tests pass.
- The website is accessible through a public URL.
