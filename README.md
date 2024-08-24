# HZTDE

Html Zu Text Document Editor. An editor that uses a similar syntax to markdown that can be used to write documents that are ready to print from the web browser.

Files are saved as *.ztx* files which are plain-text friendly.

## Usage

Download the HZTDE file and open it with Chrome or any Chromium based browser like Edge or Brave. Firefox is not compatible because it does not support the `contenteditable="plaintext-only"`😔.

The document is organized into sections which each contain a seperate block level element(heading, paragraph, image, lists, code blocks, tables, ...), which in them can contain inlne elements(bold, italic, superscript, subscript, inline text, and highlighted text).

An example for all block and inline elemets can be seen in the default document that is automatically loaded by opening `HZTDE.html`.

Upon loading a file everything is put into 1 section which can automatically be broken up using the keyboard shortcut `Alt + b`. To open an already existing *.ztx* file use `Alt + o`. To save it use `Alt + s`. *Note: if you use `Ctrs + s` the document will be saved as html which we don't want.* To join 2 or more sections use `Alt + j`, *make sure you select them while none of them are being edited*. Empty blocks still remain and apear in the browser prewiew, but aren't shown when printing. To remove any section use `Alt + r`.

Embedding raw HTML is also possible as long as it doesn't contain any blank lines because `Ctrl + b` will cause them to be seperated, causing errors.
