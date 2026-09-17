🛡️ CodeSentinel AI

CodeSentinel AI is an intelligent code-review platform designed to analyze source code for potential bugs, security vulnerabilities, performance issues, anti-patterns, and code-quality problems.

It provides developers with actionable feedback through an easy-to-use web interface and supports both a local heuristic analysis engine and optional LLM-powered reviews using OpenAI or Gemini.

🚀 Live Demo:-https://sentinelcode.netlify.app/

CodeSentinel AI

✨ Features
🔍 Intelligent Code Review

Paste your source code into the editor and run an automated review to identify potential issues.

The analyzer categorizes findings into:

🔴 Critical — Bugs and security vulnerabilities

🟡 Warnings — Anti-patterns and potentially problematic code

🔵 Info — Performance-related observations

🟢 Suggestions — Code style and cleanliness improvements

🤖 AI-Powered Analysis

CodeSentinel provides two analysis approaches:

Local Heuristic Engine — Performs rule-based analysis without consuming API tokens.

OpenAI Integration — Enables LLM-backed code analysis.

Gemini Integration — Provides an alternative LLM-based review engine.

💻 Multi-Language Support

The interface allows users to select the programming language before performing a review, making the platform suitable for analyzing different types of source code.

🧹 Code Utilities

The application includes utilities such as:

Clear editor

Trim unnecessary whitespace

Load vulnerable sample code for testing

📊 Code Health Dashboard


After a review, the dashboard presents an overview of the code's health, including counts for:

Bugs & Security

Anti-patterns

Performance

Style & Cleanliness

⚡ Complexity & Security Checks

The analyzer can inspect code for patterns related to:

Security injections

Memory-related issues

Algorithmic complexity

Potential bugs

Poor coding practices

🛠️ How It Works

The basic workflow is:

User enters source code

        ↓
        
Select programming language

        ↓
Select analysis engine

        ↓
Run Code Review

        ↓
Analyze code patterns

        ↓
Identify potential issues

        ↓
Categorize findings

        ↓
Display actionable feedback

The local analysis engine can provide feedback without sending code to an external LLM.
CodeSentinel AI can be useful for:

👨‍💻 Developers reviewing code before deployment

🎓 Students learning secure coding practices

🔐 Identifying common security vulnerabilities

⚡ Finding potential performance bottlenecks

🧹 Improving code readability and maintainability

📚 Learning from automated code-review feedback

🔑 AI Provider Configuration


For LLM-powered analysis, users can optionally configure:

OpenAI API
Google Gemini API

API credentials should be kept private and should never be committed directly to the repository.
