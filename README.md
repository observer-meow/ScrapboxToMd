# ScrapboxToMarkdown
Convert Scrapbox json file to a folder of markdown files.
## Usage
Place convert.js, mod.ts, and exported Scrapbox on your user folder. Install deno if you don't have them.

`deno run --allow-run --allow-read --allow-write mod.ts SCRAPBOX_EXPORTED_FILE.json PROJECT_NAME`
- The project `PROJECT_NAME` will be used as the source of icons.

New folder will be generated.
