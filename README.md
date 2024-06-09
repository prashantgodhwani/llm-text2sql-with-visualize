<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">LLM-TEXT2SQL-WITH-VISUALIZE</h1>
</p>
<p align="center">
    <em>Converse, Query, Illuminate-Data at Hand!</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/last-commit/prashantgodhwani/llm-text2sql-with-visualize?style=flat-square&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/prashantgodhwani/llm-text2sql-with-visualize?style=flat-square&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/prashantgodhwani/llm-text2sql-with-visualize?style=flat-square&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat-square&logo=Jupyter&logoColor=white" alt="Jupyter">
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

The `llm-text2sql-with-visualize` project revolutionizes data manipulation and analysis by enabling users to interactively convert natural language queries into structured SQL statements. At its core, the project empowers users to engage in conversational interfaces with Large Language Models (LLMs), leveraging these models to translate text into actionable SQL code. This innovative tool simplifies complex data operations, streamlining the process for non-technical professionals and developers alike, ultimately driving faster insights and informed decision-making. Furthermore, it also helps with visualization of responses of SQL queries using function invocation.

---

##  Features

|     |   Feature          | Description  |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | This is a Jupyter Notebook (ipynb) file, part of an open-source repository that uses Large Language Models (LLMs) to convert natural language queries into structured SQL statements. The architecture is centered around LLM-powered text-2-SQL conversion. |
| 🔩  | **Code Quality**  | High-quality code written in Python with proper indentation, variable naming conventions, and minimal magic numbers. Code style adheres to best practices. |
| 📄  | **Documentation** | Excellent documentation within the project file (chat_with_data.ipynb). The code is well-commented, providing clear explanations of functionality. Additional documentation may exist outside this file. |
| 🔌  | **Integrations**   | Integrated with LLM-based text-2-SQL converter and Jupyter Notebook environments (`ipynb`, `jupyternotebook`). Dependent on other projects (e.g., the repository's overall architecture). |
| 🧩  | **Modularity**     | Code is organized into logical sections (chat_with_data) with clear separation between components. Easy to modify or reuse individual parts of the codebase. |
| 🧪  | **Testing**        | No specific testing frameworks or tools mentioned, but Jupyter Notebook environments can facilitate exploratory testing and debugging. More comprehensive testing may exist outside this file. |
| ⚡️  | **Performance**    | As a Jupyter Notebook-based project, performance might be subjective, dependent on system resources (CPU, memory), and user interaction (input, output). No explicit performance optimization or resource utilization metrics mentioned. |
| 🛡️  | **Security**       | Since this is an open-source project with no sensitive data or unauthorized access controls mentioned, security measures focus on protecting the integrity of code and data through proper versioning, backup, and change management. |
| 📦  | **Dependencies**   | Dependent on Jupyter Notebook (`ipynb`, `jupyternotebook`) environment and LLM-based text-2-SQL converter (mentioned but not specific). Additional dependencies may exist in the repository's overall architecture. |
| 🚀  | **Scalability**    | Since this is a proof-of-concept project, scalability might be limited to individual user interactions or small-scale testing. More comprehensive load and performance testing would be necessary for large-scale production deployments. |

---

##  Repository Structure

```sh
└── llm-text2sql-with-visualize/
    ├── chat_with_data.ipynb
    └── data
        ├── database_tables.csv
        └── train_titanic.csv
```

---

##  Modules

<details closed><summary>.</summary>

| File                                                                                                                     | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ---                                                                                                                      | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| [chat_with_data.ipynb](https://github.com/prashantgodhwani/llm-text2sql-with-visualize/blob/master/chat_with_data.ipynb) | This code file, `chat_with_data.ipynb`, is a crucial component of the `llm-text2sql-with-visualize` repository, which focuses on leveraging Large Language Models (LLMs) to convert natural language queries into structured SQL statements. The main purpose of this file is to facilitate a chat-based interface for users to interact with the LLM-powered text-to-SQL conversion process.
**Critical features:** 
1. **Interactive Query Generation**
This code enables users to input natural language questions and receive corresponding SQL queries as output, showcasing the repository's core functionality.
2. **LLM Integration** 
The file incorporates the LLM-based text-to-SQL converter, allowing users to engage with the system and observe its ability to translate text into structured SQL queries.By achieving this goal, `chat_with_data.ipynb` plays a vital role in demonstrating the capabilities of the repositorys overall architecture, which aims to simplify data manipulation and analysis through conversational interfaces. 
3. **Visualization using Method Invocation**
The application also generates respective visualization using Method invocation with Llama 3 on Groq, and powered by open-source Code Interpreter SDK by E2B. The E2B Code Interpreter SDK quickly creates a secure cloud sandbox powered by Firecracker. Inside this sandbox is a running Jupyter server that the LLM can use.

</details>

---

##  Getting Started

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the llm-text2sql-with-visualize repository:
>
> ```console
> $ git clone https://github.com/prashantgodhwani/llm-text2sql-with-visualize
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd llm-text2sql-with-visualize
> ```
>

###  Usage

<h4>From <code>source</code></h4>

> Run llm-text2sql-with-visualize using the command below:
> ```console
> $ jupyter nbconvert --execute notebook.ipynb
> ```
---

##  Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Report Issues](https://github.com/prashantgodhwani/llm-text2sql-with-visualize/issues)**: Submit bugs found or log feature requests for the `llm-text2sql-with-visualize` project.
- **[Submit Pull Requests](https://github.com/prashantgodhwani/llm-text2sql-with-visualize/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/prashantgodhwani/llm-text2sql-with-visualize/discussions)**: Share your insights, provide feedback, or ask questions.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/prashantgodhwani/llm-text2sql-with-visualize
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="center">
   <a href="https://github.com{/prashantgodhwani/llm-text2sql-with-visualize/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=prashantgodhwani/llm-text2sql-with-visualize">
   </a>
</p>
</details>

---

[**Return**](#-overview)

---
