# Curve-letters
A place to publish scientific papers researching Curve and DeFi in general

## Contribution

### Style

Add style to the beginnig of document
```latex
\documentclass[notitlepage]{revtex4-2}
\usepackage[utf8]{inputenc}
\usepackage{geometry}
\usepackage{xcolor}
\geometry{a4paper, margin=1in}
\usepackage{graphicx}
\usepackage{amsmath}
\usepackage[margin=5pt]{subfig}
\definecolor{darkgreen}{rgb}{0.00,0.50,0.25}
\definecolor{darkblue}{rgb}{0.00,0.00,0.67}
\usepackage[breaklinks,pdftitle={titlel}, pdfauthor={Author},colorlinks,urlcolor=blue,citecolor=darkgreen,linkcolor=darkblue]{hyperref}
\graphicspath{{pdf/}}
```

### Project structure

.pdf files are in `/articles directory, project sources are in '/sources'