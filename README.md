CodeSentinel AI 🛡️

An intelligent, instant code-review tool that analyzes source code for security vulnerabilities, runtime bugs, performance bottlenecks, and style antipatterns. Built with a responsive split-pane interface and an automated rule-matching static analysis engine with optional LLM integration.

🚀 Live Demo

Hosted URL:https://sentinelcode.netlify.app/

✨ Features

Split-Pane Architecture: Synchronized line-numbered code editor on the left with categorized issue findings on the right.

Categorized Issue Severity:

🔴 Critical: Direct bugs, SQL/XSS injections, arbitrary execution risks (eval), and hardcoded secrets.

🟡 Warning: Resource leaks, unhandled exceptions, and blocking synchronous calls.

🔵 Info: Algorithmic complexity warnings ($O(N^2)$ loops) and loose equality pitfalls.

🟢 Suggestion: Clean code idioms, modern syntax usage (let/const over var), and formatting.

Dynamic Metrics Bar: Instant calculation of an overall Code Health Score alongside severity counters.

Actionable Remediation: Displays line-specific before/after diff snippets with one-click copy support.

Zero-Latency Offline Mode: Inspects code instantly in-browser without sending your proprietary code to third-party servers by default.

BYOK (Bring Your Own Key) Support: Optional live inference toggle for Google Gemini and OpenAI models.

🛠️ Tech Stack

Frontend & Core Engine

Layer

Technology

Details

Markup & Layout

HTML5

Semantic structure with accessibility attributes

Styling

Tailwind CSS & Modern CSS3

Responsive dark mode theme, custom scrollbars, and diff states

Logic & Interactivity

Vanilla JavaScript (ES6+)

Line syncing, event handling, dynamic UI rendering

Iconography

Lucide Icons

Clean SVG UI indicators

Typography

Google Fonts

Inter for interface UI, Fira Code for monospace editor

Optional Cloud AI Providers

Google Gemini API: gemini-2.5-flash for automated code explanations

OpenAI API: gpt-4o-mini with structured JSON schema outputs

Hosting & Deployment

Platform: Netlify (Continuous Deployment via Git / Netlify Drop)

⌨️ Shortcuts

Shortcut

Action

Ctrl + Enter / Cmd + Enter

Trigger immediate code review

Tab

Insert 4-space indentation within the editor
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
