# Module 02 — Source-Verified Research Assistant

## 1. Purpose
To provide an AI-powered research assistant that helps users understand Ayurveda through reliable classical references and modern scientific research.

## 2. Main Features

1. Ask questions in natural language.
2. Search the Ayurveda knowledge database.
3. Retrieve relevant classical Ayurveda references.
4. Retrieve relevant scientific research papers.
5. Generate answers supported by citations.
6. Display source links and available publication details.
7. Allow users to open and read the original sources.
8. Maintain research conversation history.
9. Allow users to ask follow-up questions.

## 3. Evidence Classification

The system should distinguish:

- Traditional Ayurvedic knowledge
- Historical and textual references
- Laboratory research
- Animal studies
- Human clinical studies
- Systematic reviews and meta-analyses

Do not treat traditional use or laboratory findings as proof of clinical effectiveness.

## 4. Example User Journey

User asks:

"What does Ayurveda say about Ashwagandha, and what does modern research indicate?"

The system should:
- Retrieve relevant classical references.
- Retrieve relevant scientific papers.
- Separate traditional descriptions from modern findings.
- Summarize the evidence.
- Display citations and source links.
- Identify limitations and uncertainty.

## 5. Interface Requirements

- Chat interface
- Search bar
- Source citations
- Evidence category labels
- Source detail panel
- Conversation history
- Follow-up question support

## 6. Data Requirements

Each research source should contain:
- Title
- Author or organization
- Publication date
- Source type
- DOI, PMID or original URL when available
- Relevant text or abstract
- Page or section reference when available
- Licence and access information
- Verification status

## 7. Important Rules

- Never fabricate citations.
- Never invent classical verses.
- Show the original source wherever possible.
- Distinguish traditional claims from modern evidence.
- Clearly communicate uncertainty.
- Do not present the assistant as a substitute for medical professionals.

## 8. Initial MVP

Start with:
- Ayurveda question-answering
- Retrieval from a limited verified source library
- Citation display
- Basic research-paper retrieval
- Evidence classification
