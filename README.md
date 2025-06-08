# Creating a Chart with Animated Background

+ description

## 📊 Final Result

<div style="text-align: center;">

  <img src="./video/gpt-claude-gemini-3000.aep_AME/gpt-claude-gemini-animated-background-3000.gif" alt="SLM Comparison by Knowledge Cutoff Date, Max Tokens, and Price" width="800" />

  <p style="color:gray; font-style: italic; margin-top: 0.5em;">
    Matplotlib Chart with Animated Background Added via Ae
  </p>

</div>


## 🚀 Quick Start

### Prerequisites
- Python 3.12+
- Google Gemini API key

### Installation
```bash
# Clone the repository
git clone https://github.com/yauheniya-ai/legal-agent
cd legal-agent

# Create virtual environment (recommended: use uv for speed)
uv venv --python=3.12
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
uv pip install -r requirements.txt
```

### Usage
1. Open `gpt-claude-gemini.ipynb` in your IDE or in Jupyter
2. Run all cells to process the 10-K documents and generate analysis
3. Open video editing software (e.g. Adobe Ae, Adobe Express) and place the chart with transparent background over the background video
4. Export as a gif
5. For sharing large gif files use Git LFS (see below)


## Git Large File Storage (LFS) 

```bash
brew install git-lfs

# Update global git config
git lfs install

# Select the file types you'd like Git LFS to manage
git lfs track "*.gif"

# Make sure .gitattributes is tracked
git add .gitattributes
```