# AMJ latex template

## 🧐 Why use AMJ latex template
When I wrote my thesis I had to use the AMJ citation format according to these [specifications](https://aom.org/docs/default-source/publishing-with-aom/aom_journal_style_guidea3b84b773e3649569a17a05e14cc6eaf.pdf?sfvrsn=f94177b2_2). <br>
This proved to be difficult, as there was no latex template found accross the web that fit the criteria 😠. <br>
So I spend hours going back and forth to get as close as possible to the needed style, so you don't need to 😀.

This is the result, which also includes a few handy latex tricks to polish the work.

## 🤩 Additional Features
- table creation with notes and backreferences
- secondary citation commands
- table entry counters

## 🤞 Usage

Feel free to use this template or look at the pre-build [overleaf version](https://www.overleaf.com/read/vbpjdtcqpwyn) with you can copy according to the [tutorial](https://www.overleaf.com/learn/how-to/Copying_a_project#Making_a_copy_of_a_project).<br>
To make the overleaf version work, you need to change your compiler to [LuaLaTeX](https://de.overleaf.com/learn/how-to/Changing_compiler)

- you need to use lualatex

<pre>
project/
├── data/
│   ├── campus_logo.png (<i>logo with color</i>)
│   ├── campus_logo_bk.png (<i>logo with black and white</i>)
│   ├── library.bib (<b>put your sources here</b>)
├── sections/ (<b>put your text here and \input{} it within the main.tex</b>) 
│   ├── abstract.tex
│   └── example.tex (<i>outlines different commands</i>)
├── setup/ (<i>you know what you do? then edit here</i>)
│   └── ...
├── LICENSE
├── README.md 
└── main.tex (<b>start file</b>)
</pre>

## 🌿 Honor where honor is due 

**By using this template you are required to include a reference in your writing according to the [LICENSE](https://creativecommons.org/licenses/by-sa/3.0).**