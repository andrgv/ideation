# Chrome Extension Idea: Equation Image Extractor from LaTeX

## Authors

Andrea González Varela

## Problem Statement

Many students and professionals encounter mathematical equations rendered as images or non-editable formats in PDFs, websites, and scanned documents. This makes it difficult to extract, edit, or reuse those equations in LaTeX-based documents or tools. The pain point is especially significant in academic environments where accurate mathematical notation is essential. This Chrome Extension will allow users to easily extract LaTeX equations from images or web content and convert them into editable LaTeX code, streamlining workflows and reducing manual transcription errors.

## Target Audience

This extension is aimed at students, educators, researchers, and technical professionals who regularly work with mathematical content. Users are likely to be engaged in STEM fields, use LaTeX for documentation or presentations, and frequently browse academic content online. The audience includes people taking courses like CIS 1600, where math-heavy documents are common.

## Description

Equation Image Extractor from LaTeX is a Chrome Extension that allows users to extract equations from websites or uploaded document images and convert them into LaTeX code. With a simple right-click or toolbar action, users can generate editable LaTeX that can be copied directly to the clipboard or pasted into other applications.

## Selling Points

1. Converts image-based or embedded equations into editable LaTeX code  
2. Supports both web page scraping and image input (e.g., screenshots, PDFs)  
3. Clipboard integration for instant copy-paste into LaTeX editors  
4. Uses advanced OCR or LLM-based image-to-text conversion for high accuracy  
5. Saves time and reduces transcription errors in academic and professional work  

## User Stories

1. As a student, I want to extract LaTeX code from an equation image on a webpage so that I can reuse it in my assignment.  
2. As a researcher, I want to convert PDF-based equations into LaTeX so that I can include them in my paper without retyping.  
3. As a professor, I want to quickly capture equations from websites for my lecture slides in LaTeX.  
4. As a developer, I want to right-click on an equation image and select "Extract LaTeX" to generate the corresponding code.  
5. As a learner, I want the extracted LaTeX code to be copied to my clipboard automatically so that I can paste it directly into Overleaf.  

## Notes

This project will require integrating an OCR model or LLM to recognize equations from images, which might involve using an external API or running inference locally. Handling equations from different sources will need customized logic. For instance, websites that render math via MathJax may expose LaTeX directly, while PDFs and image-based equations will require visual recognition. API key management and privacy considerations will also be important. It will be a popular and ambitious project, especially in math-heavy academic settings.

## References & Inspiration

- [Mathpix](https://mathpix.com/)  
- [KaTeX](https://katex.org/)  
- [MathJax](https://www.mathjax.org/)  
- [CIS 1600](https://www.seas.upenn.edu/~cis1600/)