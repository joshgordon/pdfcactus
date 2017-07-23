# pdfcactus
A suite of tools that is a wrapper around ghostscript to manipulate PDF files

pdfcat
------

Merges two or more PDF files together into one.

Example: `pdfcat -o full_report.pdf report1.pdf "report part two.pdf"`

this will take `report1.pdf` and `report part two.pdf` and merge them into
`full_report.pdf`.

pdfcut
------

Cuts out parts of a pdf file into another PDF file.

Example: `pdfcut -o report_part_1.pdf -f1 -t3 full_report.pdf`

This will take pages 1, 2, and 3 of `full_report.pdf` and output them to
`report_part_1.pdf`
