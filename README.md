# Creating a Chart with Animated Background

This project shows how to build a data-rich chart (token limits, prices, and model release dates) and overlay it on an animated scene for maximum visual impact.

## Final Result

![Animated Chart Background](https://raw.githubusercontent.com/yauheniya-ai/animated-chart-background/main/video/gpt-claude-gemini-3000.aep_AME/gpt-claude-gemini-animated-background-3000.gif)


## Quick Start

### Installation
```bash
# Clone the repository
git clone https://github.com/yauheniya-ai/animated-chart-background
cd animated-chart-background

# Create virtual environment (recommended: use uv for speed)
uv venv --python=3.12
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
uv pip install -r requirements.txt
```

## Usage
1. Open `gpt-claude-gemini.ipynb` in your IDE or in Jupyter
2. Run all cells to load the data and generate the chart
3. Open your video editing software (e.g. Adobe After Effects, Adobe Express) and place the chart (with transparent background) over the background video
4. Export as a looping GIF or MP4
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


## License

The MIT License permits free use, modification, and distribution of software with attribution.

## Further Information

There is a detailed [article on Medium]() explaining the implementation steps.