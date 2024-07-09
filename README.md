# FOSS empty page templates

## How to run

Compile the LaTeX document using your standard PDFTeX with MikTeX, TeXLive or whatever you are using.

### Conversions

- Big PDF -> individual pages PDF: [PDF24](https://tools.pdf24.org/en/split-pdf)
- PDF -> SVG: [PDF24](https://tools.pdf24.org/en/pdf-to-svg)
- SVG -> PNG: [Inkscape](https://inkscape.org/) cli: `& "C:\Program Files\Inkscape\bin\inkscape.exe" -o A4_light.png -w 8640 .\A4_light.svg`

for any other conversion i will probaby use FFMPEG

## How it started

I wanted to write on squared paper on my tablet. I researched some online generators but none had any "dark mode" pages, and there was always a watermark.

So I just did it myself and wrote (well researched) a LaTeX script to generate this.

I lated discovered that my notetaking app wont display highlighters on a black PDF, but on black images. (Samsung Notes can be difficult in places where you dont expect it.)<br>
So in any release you can find the full PDF generated with LaTeX, and a folder "conversions". Inside there are the individual Pages as PDF and some Image formats. (for the moment SVG and PNG, but could be more in the future)
