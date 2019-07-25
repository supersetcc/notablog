# notablog

Generate a minimal blog from Notion.so.

## Getting Started

1. Duplicate my [BlogTable template](https://www.notion.so/937c97eb6efb47f5864dc7fa66bbe88a?v=7076048baf9842238b74342f6b491c5b) on Notion.
2. Make the table you've duplicated **public**.
3. Clone the [`notablog-starter`](https://github.com/dragonman225/notablog-starter) repository and install packages.
   ```bash
   git clone https://github.com/dragonman225/notablog-starter.git
   cd notablog-starter && npm install
   ```
4. Open `config.json`. Change `url` field to the URL of the table you've duplicated.
5. Issue command `npm run generate`. Generated site is the `public` folder.

## More Information

* To edit CSS styles, look for files in `public/css`. (Notice : This folder may be moved in the future.)
* To edit layouts, look for files in `layout`. These are [Squirrelly](https://squirrelly.js.org/) templates.
