# Default Project

A standardized, multi-paradigm software development project template configured with Git, Node.js, and Python support.

## Project Structure

```text
├── src/            # Source code (Node.js / Python modules)
├── tests/          # Test suites
├── docs/           # Documentation
├── scripts/        # Build and utility scripts
├── .env.example    # Environment variables template
├── .gitignore      # Git ignore rules
├── package.json    # Node.js project configuration
└── requirements.txt# Python dependencies
```

## Getting Started

### Prerequisites

- **Git** (v2.x+)
- **Node.js** (v20+) & **npm**
- **Python** (v3.10+)
- **GitHub CLI** (`gh`)

### Installation & Setup

1. Clone the repository and navigate into the project directory:
   ```bash
   git clone <repository-url>
   cd "Default Project"
   ```

2. Configure environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your specific configuration
   ```

3. Install Node.js dependencies:
   ```bash
   npm install
   ```

4. Set up Python virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   # On Windows (PowerShell):
   .venv\Scripts\Activate.ps1
   # On macOS/Linux:
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

## Running & Testing

- Run Node.js application:
  ```bash
  npm start
  ```
- Run Python tests:
  ```bash
  pytest
  ```

## License

MIT
