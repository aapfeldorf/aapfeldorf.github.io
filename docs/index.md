# Claude Artifacts
<!---!!! note "[Anthropic official documentation on Artifacts](https://support.anthropic.com/en/articles/9487310-what-are-artifacts-and-how-do-i-use-them)"
    *Artifacts allow Claude to share substantial, standalone content with you in a dedicated window separate from the main conversation. Artifacts make it easy to work with significant pieces of content that you may want to modify, build upon, or reference later.* --->

<!--**<span style="background: linear-gradient(in oklch longer hue 90deg, oklch(0.68 0.1379 0), oklch(0.68 0.1379 360)); background-clip: text; color: rgb(0 0 0 / 0)">it's okay to slay</span>** -->

## What are Artifacts?

Artifacts are a feature built into the website for the large language model (LLM) Claude. They allow Claude to generate content beyond basic chat messages that show up separate from the conversation. This feature is perfect for displaying specific formats or visuals such as webpages, diagrams, charts, and formatted documents.

While Claude is geared towards coding and writing applications, almost anyone can take advantage of its tools, even users with minimal-to-no coding experience. This guide is intended for those with minimal coding skills or anyone who may be curious about what Claude can do for them in their day-to-day life. While Claude provides [documentation and general information](https://support.anthropic.com/en/articles/9487310-what-are-artifacts-and-how-do-i-use-them) on Artifacts, the documentation uses technical language that assumes you have a higher base-line knowledge of LLMs than most people. This guide explains in accessible terms how you can use Artifacts and what features may suit your needs best.

## What is this guide?

This guide teaches you how to use Claude to create a variety of helpful artifacts for your everyday life. It covers items like personal tools and websites, various forms of data visualization, and document templates for you or others to use. Remember, Claude and other forms of generative AI aren't perfect. They might not produce exactly what you envision or provide fully accurate information. For this reason, when using Claude or other form of generative AI, remain informed and practice general internet safety, especially regarding personal or sensitive information.

## Outline

* General Artifact Features (This Page)
* [Coding Uses](coding-uses.md)
* [Data Visualization](data-visualization.md)
* [Document Templates](document-templates.md)
* [Ethical Implications](ethics.md)
* [About This Guide](about.md)

## General Artifact Features

>![Example Artifact window showing React code for a to-do list](https://hackmd.io/_uploads/BJbzSKtTyx.png)
> An example Artifact window showing the code for a simple to-do list user interface.
>
### Preview/Code Toggle

In the top left of the example Artifact window you will see a toggle for the options **"Preview"** and **"Code"** (the eyeball and the ```</>``` respectively). Toggling allows you to either see the code Claude has generated or the visual components created by the code. Depending on your use case, no visuals may need to be displayed, so the toggle will not appear. The toggle appears when generating code that produces a user interface, data visualizations, or other types of graphical output.

### Copy and Download

In the top right of the example Artifact window, a **"Copy"** button with a drop down menu for downloading the Artifact is displayed. 

**"Copy"** allows you to copy the Artifact code/content to your clipboard so that you can paste it wherever you may need.

**"Download as ..."** will turn the Artifact content into a file and download it to your device. The file type depends on what Claude generated; for example, a document template might create a Markdown file while code for a program in the language C will generate as a `.c` file.

### Publish

The publish tool makes your Artifact publicly-accessible. Publishing won't make the conversation publicly searchable, but individuals with the public link (generated when published) will be able to view your Artifact in their browser. The Artifact code cannot be edited directly from this public link, but it can be **"Remixed"**, allowing any user to create their own Claude conversation with the Artifact. Any published Artifact must be republished to show up-to-date changes and can also be unpublished at any time.

### Claude's Analysis Tool

The Analysis Tool allows Claude to run code that processes, analyzes, and provides real-time visualizations of submitted data. This allows users to work alongside Claude to generate Artifacts for more specific coding needs, especially for data visualization or document formatting. The analysis tool can be enabled through user settings under the **"Profile"** tab under **"Feature Preview"**.

## Types of Artifacts

Claude is primarily known for its ability to generate code for a variety of use cases.

| Type | Use Cases |
| --- | --- |
| **Code** | Functions and algorithms |
| **Markdown** | Document templates (guides, reports, etc.) |
| **HTML** | Web pages and user interface design |
| **Mermaid** | Diagrams and charts |
| **React** | User interface components and data visualization |