## :bear: Bear's Resume - A Minimalist LuaLaTeX Resume 

A clean, simple, and ATS-friendly resume template for software developers. It's easy to read, easy to edit, and made so you don't waste your time with Google Docs or Canva (like I did).

This layout is based on the popular [sb2nov/resume](https://github.com/sb2nov/resume/), but rebuilt with LuaLaTeX, Makefile + Docker for proper UTF-8 handling, helping it get past ATS parsers (Applicant Tracking Systems).

## How to Use

<!-- You have two options:

### Option 1: Overleaf (Easiest Method)

Get started immediately by using the [Overleaf template](https://www.overleaf.com/latex/templates/bears-resume/gqxmqsvsbdjf)

### Option 2: Local Build (Docker + Make)

Prerequisites: You'll need **Docker** and **make** installed. -->

### Build using Docker and Makefile

```sh
# Clone this repository
git clone https://github.com/luisbernardinello/resume.git
cd resume

# Edit bearsume.tex with your information

# Compile the PDF (runs lualatex twice)
make pdf

# Clean up auxiliary files (optional)
make clean

```

### License

Format is MIT but all the data is owned by Filipe Bernardinello.
