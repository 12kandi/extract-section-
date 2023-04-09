# extract-section
## Applying Textual Analysis using Corporate Compensation Discussion and Analysis (CD&A):
this porgram is used to extract a specific section in corporate annual meeting for shareholders and proxy statement. To be able to extract the CD&A section, I need to tell the computer the starting and ending marks. I had to read many documents to see the pattern of the data so that I can decide on the starting and end marks.
The second task is to apply textual analysis to generate many textual constructs. For example, how many times the company use performance keywords. I was given the performance dictionary (library) and I generate a performance construct for every firm across years. Same method is applied to other textual features, such as the positive keywords, negative keywords, strategic keywords, and so on. 
In addition, I generated a new concept, called the distance between performance and compensation keywords. Furthermore, I was asked to create a variables called “firm specificity” which measures how specific managers are when they report the firm performance. I calculate the frequency of “numbers”, “dollar sign”, and “percentage”. 

## Pain Points:
The issue that I face is that firms have different structure and different keywords used to signal the CD&A. I had to develop many loops and conditions to be able to extract the section. I kept sharing the output with my client and get his comments and reflects that on my code until I was able to crawl around %90 of CD&A section. 
## Outcomes Learned:
develop many loops and conditions to be able to extract the section.


