# zine-arranger
Arranges PDFs into printable zine layouts

Use the tool online here: https://nashhigh.itch.io/zinearranger

Arrange multi-page PDF files into a printable zine layout!

Supports the following zine formats:

* Minizine (Eighth-Size)
* Quarter Size
* Half Size

With options for:

* Portrait/Landscape orientation
* Single/Double sided printing (for Mini's & Quarter Size)
* Side/Top fold (for Mini's & Quarter Size)
* Paper size (US Letter / A4 / Custom)


Tips

* This tool uses your browser's print function to actually lay everything out. You can print it directly from the tool, or you can Print to File / Save as PDF to save the printable version. Since different browsers have different print tools, it's possible some of them won't play nicely with this tool, but so far it seems to work on the ones that I've tried.
* For double-sided printing, you may need to tell your printer to "Flip on the long edge" or "Flip on the short edge". The pages should always be laid out to flip along the side of the zine, so choose based on whether the side is long or short!
* It's always a good idea to set your Page Size to the actual dimensions of the individual pages once they're printed & folded, to ensure you've got the correct aspect ratio. If the ratio isn't correct, Zine Arranger will fit the pages as best it can, but you might end up with a little extra space at the top & bottom, or at the sides. (If you're using A-size paper, you actually don't need to worry about this, because your ratios will always be the same!)
      - Here's a quick cheat-sheet of page sizes (for US Letter size paper, Portrait orientation; switch 'em around if you're doing Landscape!):
            Half Size - 5.5"x8.5"
            Quarter Size - 4.25"x5.5"
            Eighth Size / Mini - 2.75"x4.25"

Troubleshooting

* Your zine prints & the folds aren't lined up anymore, or the page alignment gets weird.
    - The most common culprit is the print app shrinking the content to fit on the page. Look for a Scale section and try to set it to Actual Size or 100%.
    - If you don't want to re-print your zine, you can also generally get your layout/folding back to normal by just trimming off the blank margins that the printer added (Depending on your zine, it may be hard to tell where the extra margins are. Often they're around 0.5" though.)
    - If changing the Scale settings didn't help, setting the Page Size as mentioned in #3 above might also help!That generally shouldn't affect the folding aspect, but it might place your page content a little off from where you want it.
* When you print, there's a white border around the edges & some of your content gets cut off.
    - Most printers can't print all the way to the edge of the paper, so if you have a colored background or content going all the way to the edge, some of it might get cropped off.
    - In this case, you might actually want to set the Scale in the printer settings to Scale to Fit or Fit Page (or something like that), or you could manually set the percentage to something like 90%.
    - When you set it to fit to page, you are going to run into Problem #1 from above, where the folding/layout gets wonky--but don't worry! All you need to do is take a paper cutter and cut off the white/empty border. Once you trim the border, the layout & folding should all work again, and you'll just end up with a slightly tinier zine, but with content that can go right up to the edge!

Notes

* A very special thanks to Rowan Merewood for creating the tutorial "Create a printable zine with CSS", which was one of the main resources I relied on for getting started with this project.
* A second round of thanks to the developers of PDF.js, because I have no clue how to work with PDF's on my own.
