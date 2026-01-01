## Project: SmartDocs or *whatever creative name you like*

### 1. Project Overview
The goal of this project is to build a Intelligent Document Platform. Unlike a standard search engine that looks for keywords, this allows users to upload their own private files and "ask questions" or "chat" with them. The system acts as a "Second Brain," retrieving relevant information from a library of documents to answer user queries accurately with citations.

---

### 2. Functional Requirements

#### **A. Document Ingestion**
* **Format Support:** The system must process at least 2 distinct file formats (e.g., `.pdf`, `.docx`, `.txt`, `.md`).
* **Library Management:** A user interface to upload new files, list currently indexed files, and delete documents from the knowledge base.
* **Persistence:** All uploaded documents and their processed data must persist across server restarts.

#### **B. The "Chat with Data"**
* **Contextual Intelligence:** The AI must generate answers based strictly on the provided document(s) library.
* **Multi-Doc Reasoning:** The system should be able to generate an answer by pulling information from multiple files at once.
* **Verification (Citations):** Every response must include a reference to the source document to ensure transparency.

#### **C. User Interface**
* **File/Folder Dashboard:** A clean view to manage the document lifecycle.
* **Conversational UI:** A messaging interface that handles user queries and displays AI responses.

---

### 3. Stretch Goal: Optimization 🚀
**Requirement:** Implement a hierarchical **Folder Structure** for document organization.
* **User Feature:** Users can toggle/select specific folders in the UI.
* **AI Feature:** The chat engine must "scope" its retrieval to only the selected folder. 
* **Optimization Goal:** Minimize noise and improve retrieval accuracy by filtering the search space before performing vector calculations.


---

### 4. Technical Constraints & Skills
To successfully complete this project, you must address the following technical layers:

* **API Layer:** Develop a robust backend API to handle file upload/streams, document status, and query processing.
* **UI Layer:** User interface to manage document lifecycle and messaging interface for chatting with the document(s).
* **Data Structures:** Implement a strategy for **text segmentation** (splitting large documents into manageable units) and metadata mapping.
* **Search Algorithm:** Implement an algorithm to find the most relevant sections of text for a given query (e.g., Vector-based Similarity Search, Keyword-based Indexing, or Hybrid Search).
* **AI Integration:** Leverage a Large Language Model (LLM) to act as the reasoning engine for the retrieved data.

---

### 5. Timeline
* **Target Completion:** 2–3 Weeks.
* **Demo Ready:** A fully working end-to-end prototype including UI, API, and AI logic.
