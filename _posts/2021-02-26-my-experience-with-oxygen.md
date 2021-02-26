# My Experience with Oxygen: No Laptops Were Harmed in the Making of This Project

I was assigned to code pages 16 through 19 of “The Yellow Wall-paper” by Charlotte Perkins Stetson. “The Yellow Wall-paper” is a narrative-style short story written in 1892, providing a glimpse into the societal attitudes and gender norms surrounding women’s health during this era. 

Before coding, I used Google Docs to markup areas where tags would be needed. Next, I transferred the text into Oxygen, which is an XML (eXtensible Markup Language) coding program. To code, I used Text Encoding Initiative (TEI).

### Markup in Google Docs
I first went into our class Google Drive to find a document that contained the text copied from the manuscript. When I heard I would markup 4 pages, I thought the process would be painfully long. However, each page contained a few short paragraphs, which led me to breathe a sigh of relief.

I marked up page numbers, weird spacings, underlined words, crossed out words, added words, text mistakes, and em-dashes. Some areas where tags would be needed were easier to identify than others. For example, the em-dashes were easier to spot compared to text mistakes, as those required a greater attention to detail.

![Picture of Markup](https://eslupe6.github.io/eslupe6/images/markup.png)

Although using Google Docs during the markup stage gave me a better understanding of the tags and a better view of the steps I would take in Oxygen, I was still nervous about coding.

### Coding in Oxygen

When I downloaded Oxygen, I worried my laptop would crash (again). Last year I downloaded software for a class, then my laptop had what the Apple worker called “a digital heart attack.” I feared my laptop would have another heart attack, but this time it would be fatal. 

I felt relieved when the download completed, but my nerves crept up once I opened a file. Amidst the words and symbols, I had no idea where to start. After watching the tutorial from the professor, I felt more comfortable working with TEI. I also felt at-ease working with the small list of specific tags to use provided by the professor. 

However, I noticed in “author view” that there were odd spaces between sentences that were interrupted by a page break. Asking questions in class was helpful, allowing me to identify the problem. I originally started a paragraph with ```<p>``` and ended it with ```<p>``` before the page number tag, then added another ```<p>``` before the rest of the sentence on the next page. This created the weird spacing. I resolved the issue through starting the paragraph with ```<p>```, entering the page tag, continuing the sentence that started on a new page, then concluding with ```<p>``` to end the paragraph. I realized that sentences within paragraphs must stay connected to one another, with only the page tag separating them.

![Picture of Code](https://eslupe6.github.io/eslupe6/images/coding.png)

Despite how nervous I was to code, this assignment was a positive experience. I grew more confident in my coding ability, which makes me feel more prepared to tackle projects involving code in the workforce.
