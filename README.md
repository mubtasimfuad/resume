# LaTeX Resume of Mubtasim Fuad

This repository contains the LaTeX source code for my personal resume. The resume is designed to fit on one page and highlights my skills, experience, projects, and education as a backend developer.

## How to Use

### Viewing the Resume
If you just want to view the compiled PDF version of the resume, you can check the `resume.pdf` file included in this repository. 

### Compiling the Resume

If you'd like to compile the LaTeX file yourself, follow these steps:

1. **Install LaTeX**: You will need a LaTeX distribution installed on your machine. I recommend using [TeX Live](https://www.tug.org/texlive/) for Linux and Windows users, or [MacTeX](https://tug.org/mactex/) for macOS users.

2. **Clone this repository**:
    ```bash
    git clone https://github.com/mubtasimfuad/resume.git
    cd resume
    ```

3. **Compile the LaTeX file**:
    ```bash
    pdflatex resume.tex
    ```

This will generate a `resume.pdf` file from the LaTeX source. You may need to run the compile command multiple times if you use citations or references.

### Dependencies

The LaTeX resume uses the following packages:
- `fullpage`: For adjusting page margins.
- `titlesec`: To customize the section title formatting.
- `enumitem`: For better list management.
- `hyperref`: For clickable links in the PDF (links to GitHub, LinkedIn, etc.).
- `fancyhdr`: For modifying the header and footer.
- `fontawesome`: For adding icons in the contact section (GitHub, LinkedIn, etc.).

Make sure these packages are installed in your LaTeX distribution.

## Customization

Feel free to fork this repository and modify it for your own use. You can easily change the sections, fonts, and layout by adjusting the LaTeX code.

### License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT). You're free to use, modify, and distribute it as long as you credit the original author.
