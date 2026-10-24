# awesome-excel

A curated list of awesome Microsoft Excel resources - This is heavily WIP, so please feel free to contribute / upload ideas to issues!

## Symbology

Because of the nature of Excel, sometimes businesses have made commercial addins, meaning not all of these resources are free. Additionally, some resources might be password protected. As such we utilise the following symbols to denote the status of the resource.

[o_paid]: ./resources/Money.svg
[o_pass]: ./resources/Padlock.svg "Spreadsheet is passwordprotected"

- [![o_pass]](#-) - Workbook is password protected.
- [![o_paid]](#- "Link includes/leads to paid content") - Link includes/leads to paid content

## Contents

- [See Also](#see-also)
- [Formulas](#formulas)
- [Addins](#addins)
- [Templates](#templates)
- [Examples](#examples)
- [Development](#development)
  - [Libraries](#libraries)
- [Resources](#resources)
  - [YouTube Channels](#youtube-channels)
  - [Books](#books)
  - [Courses](#courses)

## See Also

We have a number of other awesome lists for Microsoft Office related topics:

- [awesome-vba](https://github.com/danielpiestrak/awesome-vba) - A curated list of awesome VBA resources

## Formulas

- [Can I Spreadsheet?](https://canispreadsheet.com/) - Cross-app formula compatibility reference — does a function/formula work the same in Excel, Google Sheets and LibreOffice? LibreOffice results are produced by actually executing each formula (across several versions), not scraped from docs. Also has a paste-a-formula checker with an Excel↔Sheets migration report and an open CC BY dataset.

## Addins

### VSTO Addins

- [![o_paid]](#- "Trial exists, License paid for") [Arixcel](https://www.arixcel.com/) - Arixcel a great addin for auditing, exploring and understanding formulas in other Excel spreadsheets.
- [![o_paid]](#- "Trial exists, License paid for") [Macabacus](https://macabacus.com/) - Keyboard shortcuts for Excel on steroids. This also has formula auditing tools. You can find out more on their [youtube channel](https://www.youtube.com/@Macabacus-Inc)

### COM Addins

- [![o_paid]](#- "Paid licenses exist for support") [QueryStorm](https://querystorm.com/features/sql-querying/) - QueryStorm is a free for personal use COM addin that allows you to query data from Excel and other spreadsheets. Paid plans are available for larger teams.

### OfficeJS Addins

- [![o_paid]](#- "Free trial exists, else payment required") [Chart Expo](https://appsource.microsoft.com/en-us/product/office/wa104380662?tab=overview) - Create beautiful charts in Excel with Chart Expo. Likely uses d3.js under the hood.
- [E2D3](https://appsource.microsoft.com/en-us/product/office/WA104379169?tab=Overview) - E2D3 uses d3.js to build some nice graph templates.
- [Excel-labs](https://www.microsoft.com/en-us/garage/profiles/excel-labs/) - Advanced Formula Environment for making software with `Lambda` formulae.
- [Vertex42 Template Gallery](https://www.vertex42.com/apps/templategallery.html) - A gallery of 400 free spreadsheet and document templates. You can also browse the templates [here](http://apps.vertex42.com/templategallery).

### VBA Addins

- [![o_paid]](#- "Payment required") [Peltier Tech Charts](https://github.com/sancarn/awesome-vba?tab=readme-ov-file#addins) - Need a chart that’s not native to Excel? Peltier Tech makes Cycle Plots, Step Charts, Clustered AND Stacked Column or Bar Charts, and more.
- [Developer specific Addins](https://github.com/sancarn/awesome-vba?tab=readme-ov-file#addins) - See Awesome-VBA for addins that are specific to VBA developers.

### macOS Tools

- [![o_paid]](#- "Free trial exists, else payment required") [Mac Excel Shortcuts](https://maccove.com) - Replicates familiar Excel keyboard shortcuts for Windows migrators on macOS.

## Templates

## Examples

- [Excel 2D & 3D Robot Arm](https://github.com/CarlKCarlK/excel-3d-robot-arm) - A playable workbook that models 2D and 3D robot arms with spreadsheet formulas, charts, form controls, and Solver.
- [Interactive 3D Rubik's Cube](https://www.reddit.com/r/excel/comments/1ingef6/i_made_an_interactive_3d_rubiks_cube_simulator_in/) - Formula-only cube simulator. Checkboxes drive the moves through iterative calculation, with no VBA.
- [15 Puzzle](https://www.reddit.com/r/excel/comments/1k79oqu/i_made_15_puzzle_in_excel_using_formulas_only_no/) - Formula-only sliding puzzle. Iterative calculation and `LAMBDA` generate solvable scrambles and swap adjacent tiles, with no VBA.
- [QR code generator](https://drive.google.com/file/d/1QGAP3RawTAqlDLSME_erQcXprZOM3p87/view) - Formula-only QR workbook. No macros, add-ins, special fonts, or internet access. [Showcase](https://www.reddit.com/r/excel/comments/1tgsicn/showcase_qr_code_generator_in_excel_without/).

## Art

- [George Lungu](https://www.youtube.com/watch?v=mlJYhXNky3g)'s amazing Excel 2003 animationsn and the maker of the [Excel roller coaster](https://youtu.be/IrVA1BBHFHw). Though these kinds of animations aren't really possible in the bloated 2008+ versions of Excel, George shows us some frankly incredible simulations and animations which were doable in Excel 2003. He hasn't posted any animations in about 5 years, but still [his website](https://excelunusual.com/) and [youtube channel](https://www.youtube.com/@EngineeringFun) show off some of the greatest Excel art of all time.
- [Tatsuo Horiuchi](https://youtu.be/OrwBc6PwAcY)'s art made entirely in Excel. This is very cool! More can be found [here](https://mymodernmet.com/tatsuo-horiuchi-excel-spreadsheet-paintings/).
- [Emma Stevens](https://design-milk.com/spreadsheet-architecture-of-emma-stevens/)' ASCII art landscapes in Excel.

## Learning Resources

### YouTube Channels

- [HotSheets](https://www.youtube.com/@HotSheets) - Excel formulae explained visually.
- [![o_paid]](#- "Links to paid content") [Other Levels](https://www.youtube.com/@OtherLevels/videos) - A creator of beautiful modern looking dashboards. They also have a [website](https://other-levels.com/) full of templates, courses and more.
- [WiseOwl - VBA Tutorials](https://www.youtube.com/watch?v=KHO5NIcZAc4&list=PLNIs-AWhQzckr8Dgmgb3akx_gFMnpxTN5) - Beginner tutorials for Excel VBA beginners.

### Books

### Courses

### Misc

- [Beautify your charts](https://i.imgur.com/WntrM6p.gif) - A short gif showing how to make charts more impactful and beautiful.

## Development

- [Excel-DNA](https://excel-dna.net/) - Excel-DNA is a free, open source, cross-platform, high-performance, native-based, C# Excel add-in framework.
- [![o_paid]](#- "Open source; xlwings PRO is paid") [xlwings](https://www.xlwings.org/) - Call Python from Excel and Excel from Python, on Windows, macOS, and Excel on the web. Supports scripting and macros, NumPy and pandas, and UDFs on Windows. The open-source library is free; xlwings PRO is a paid tier.

### Libraries

Libraries for working with workbook files outside Excel:

- [ExcelDataReader](https://github.com/ExcelDataReader/ExcelDataReader) - Lightweight C# library for reading Microsoft Excel files (Excel 2.0 through Microsoft 365).
- [ExcelJS](https://github.com/exceljs/exceljs) - JavaScript library for reading, manipulating, and writing spreadsheet data and styles to XLSX and JSON.
- [ImportExcel](https://github.com/dfinke/ImportExcel) - PowerShell module to import and export spreadsheets without Excel installed.
- [Excelize](https://github.com/qax-os/excelize) - Go library for reading and writing XLAM, XLSM, XLSX, XLTM, and XLTX files.
