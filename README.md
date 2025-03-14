# SecondSolution
My solution for the second project challenge of Python Development

1. Read Data from CSV: The script reads a CSV file named "topics.csv" using pandas. It expects the CSV to contain at least two columns: one for the "Topic" and another for the "Pages".

2. Create PDF Document: It initializes a PDF document with a portrait orientation and A4 size.

3. Add Pages for Each Topic: For each row in the CSV file:
It adds a new page to the PDF.
It sets the header to display the topic name in a larger, bold font and a specified text color.
It draws horizontal lines across the page at regular intervals.

4. Add Footers: At the bottom of each page, it includes a footer that repeats the topic name in italicized, smaller font and a lighter color.

5. Multiple Pages for Each Topic: If a topic has more than one page (as specified in the "Pages" column of the CSV), the script will add additional pages, repeating the footer and drawing lines as before.

6. Output PDF: Finally, it saves the generated PDF document as "output.pdf".