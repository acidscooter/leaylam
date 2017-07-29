<h2>http://www.leaylam.com</h2>
<p>This is my current CV/resume in HTML, it is also hosted using AWS CloudFront.</p>

<section>	    
     <h2>Week 3: HTML</h2>
     
- [ ]  <h3>1. Exercise</h3>
       <p>If you did not complete the exercises from last week, do so.</p>
           <p>If you have not read Modules 1 and 2 of the Study Book,
	   do so.</p>
	   
- [ ]  <h3>2. Exercise</h3>
       <p>The HTML used in last week’s practical is written in XHTML.
       The same code in HTML is:</p>


```
<!DOCTYPE html>
<html lang="en">
  <head>
  <title>
     A simple HTML document
  </title>
  </head>

  <body>
     <section>
       <h1>HTML Test Page</h1>
       <p>This is the first paragraph on the page!</p>
       <section>
         <h2>A Subsection Heading</h2>
         <p>This is the second paragraph on the page!</p>
       </section>
     </section>
  </body>
</html>
```

 <p>There is little difference between this HTML and the HTML of
       last week. But there is a big difference how a browser deals
       with an error.</p>
       <p>Using last week's XHTML code, create a file
       <kbd>test.xhtml</kbd> and using the code above create another
       file <kbd>test.html</kbd></p>
       <p>Test that both files are parsed correctly by the Web
       browser.</p>
       <p>Now introduce an error in both files—delete one of the
       </p> tags. Now how are they displayed by the Web browser?</p>
       <p>Copy <kbd>test.xhtml</kbd> to <kbd>alt.html</kbd> and copy
       <kbd>test.html</kbd> to <kbd>alt.xhtml</kbd>. Now display the
       alternate files in the Web browser. What has happened?</p>
       <p>How important are the file extensions to the browser?
       How important the first line of each file to the browser?</p>
       <p>Notice how <kbd>alt.xhtml</kbd> (the HTML document
       masquerading as an XHTML document) is displayed. Remove the
       error from <kbd>alt.xhtml</kbd> and display it again—what is
       the browser’s responce</p>
       <p>XHTML, being XML documents are more restrictive with errors
       and the browser will warn you if there is an error in your
       document. The advantage (and frustration) of XHTML documents
       is that the browser will error check your HTML document.</p>
       
- [ ]   <h3>3. Exercise</h3>
	Structure the text file <a href="prac\p04">Poets.txt</a>
		using XHTML markup. The file contains three poems about the
		First World War, by poets that participated in the conflict.
		Structure the file using markup so the text is sectioned
		logically by using headings, sections, paragraphs, &amp;c.

		Remember, HTML markup is used to logically
		structure the source file it is not used to format the
		browser's output.

- [ ] <h3>4. Exercise</h3>
	Format the text file <a href="prac\p04">Heracles.txt</a>
		using XHTML markup. The file contains the opening scene of Euripides'
		play Heracles. To format the file make use of Emphasised, Italic
		and Bold text, headings, a Descriptive List, &amp;c.

- [ ] <h3>5. Exercise</h3>
	Structure the text file <a href="prac\p04">TheLongShips.txt</a>
		using XHTML markup. The file contains the opening paragraph of 
		Frans Bengtsson’s book “The Long Ships”. Use the 
		<code>id</code> attribute to 
		correctly setup links to the footnotes and from the footnotes back
		to the text.
       
- [ ] <h3>6. Exercise</h3>    
	Structure the following Body Mass Index table 
		from the World Health Organisation using the <kbd>table</kbd> element.
<pre>
Classification                           BMI(kg/m<sup>2</sup>)
<strong>Underweight</strong>                               <18.50
    Severe thinness                        <16.00 
    Moderate thinness                   16.00 - 16.99
    Mild thinness                       17.00 - 18.49
<strong>Normal Range</strong>                           18.50 - 24.99
<strong>Overweight</strong>                                &#x2265;25.00
     Pre-obese                          25.00 - 29.99
     <strong>Obese</strong>                                &#x2265;30.00
          Obese class I                 30.00 - 34-99
          Obese class II                35.00 - 39.99
          Obese class III                  &#x2265;40.00 
</pre>
