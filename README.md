# Phrasing Insurrection: A Computational Study of the Grammars of Collective Enslaved Resistance Published in the *South Carolina Gazette* and *Virginia Gazette* between 1732 and 1775

This respository contains the associated data and code for "Phrasing Insurrection: A Computational Study of the Grammars of Collective Enslaved Resistance in the *South Carolina Gazette* and *Virginia Gazette* between 1732 and 1775." This study explores how digital methods, such as text mining and computational corpus linguistics, can inform novel research questions and approaches to what we can know about white colonial conceptions of collective enslaved resistance in the eighteenth century. 

> “Language, incontestably, reveals the speaker. Language, also, far more dubiously, is meant to define the other—and, in this case, the other is refusing to be defined by a language that has never been able to recognize him. People evolve a language in order to describe and thus control their circumstances, or in order not to be submerged by a reality that they cannot articulate. (And, if they cannot articulate it, they are submerged.)” - James Baldwin, “If Black English Isn’t a Language, Then Tell Me, What Is?” (1979)

Explore this project on GitHub Pages: [Phrasing Insurrection](https://chloeazehr.github.io/phrasing-insurrection/)

---

## Table of Contents

1. [Project Description](#project-description)
2. [Why Digital History? What Can Text Data Show Us?](#why-digital-history-what-can-text-data-show-us)
3. [Overview of Transatlantic and Intercolonial Slave Trades Alongside News of Enslaved Resistance](#overview-of-the-transatlantic-and-intercolonial-slave-trades-to-south-carolina-and-virginia-alongside-reports-refercing-collective-enslaved-resistance-printed-in-the-south-carolina-gazette-and-virginia-gazette-in-the-eighteenth-century)
4. [Computational Methods](#computational-techniques)
5. [Data & Corpora](#datacorpora)
6. [Computational Tools and Data/Archival Resources](#computational-tools-and-dataarchival-resources)
7. [Licenses](#licenses)
8. [Author](#author)
9. [Acknowledgements](#acknowledgements)
10. [Additional Scholarship](#additional-scholarship)

---

## Project Description
This thesis explores the scopes and limitations of what text mining for historical analysis can reveal about the cognizant work of white settlers, slave traders, merchants, ship captains, planters, and administrators to iteratively make sense of collective enslaved resistance within a social order predicated on the production of racial difference. In turn, computational text analysis brings into view habitual grammatical constructions, such as colonial reports’ reticence to situate enslaved people as syntactic agents in accounts referencing forms of occurred or intended violent black unrest, that white authors mobilized to reinforce and reshape contingent boundaries of white subjecthood, otherness, enslaveability, and property in the eighteenth century. What can re-counting words reveal?

By engaging with such questions, this project employs digital methods to re-examine the well-trod archives of North American colonial newspapers’ coverage of collective enslaved resistance, experimentally represented by text data derived from the *South Carolina Gazette* and Virginia Gazette between the 1730s and 1770s, to investigate new dimensions in the relationship between black unrest and grammar in South Carolina and Virginia’s colonial press. I employ careful computational analysis of grammatical features alongside such sources as slave trade data, colonial legislation, and secondary scholarship to examine how the rhetoric published in the *South Carolina Gazette* and *Virginia Gazette* reflected regional, colonial, and imperial conceptions of enslaved resistance. Digital methods, which render visible relatively understudied linguistic patterns in the *South Carolina Gazette* and *Virginia Gazette*’s reports on enslaved resistance, act as a window into how we might clarify the social and psychological processes that both disrupted and rationalized hereditary racial slavery in eighteenth century North America. Over the course of the study, I embrace digital historian Jo Guldi's methodology and theory of critical search—an enthusiastic attitude of openness to qualitative and quantitative methods that iteratively endeavors to find the best fit of data science methods for historical research—to reinforce and advance nuanced arguments about the relationship between structure of language, empire, hereditary racial slavery, and black resistance. This is the first computational study of text data derived from the eighteenth century colonial press regarding representations of collective enslaved resistance in North America and the greater Atlantic. 

To locate and isolate lexical descriptions of armed or violent black unrest, I define the rhetoric of collective enslaved resistance—a phrase I employ interchangeably with the historian Kellie Carter Jackson’s notion of black “political violence,”—as the language white authors used to describe, lament, and imagine acts of open enslaved insurrection, conspiracy scares, plots, and uprisings. Although the primary focus of this study is on the text published in the colonial press, I employ the term "political violence" in order to reflect the complex reality that resistance to slavery in the Americas was often a continuation of warfare from West Africa. Moreover, this transnational and diasporic framework has afforded historians new insights into how what was happening in West Africa among ethnic groups such as the Mande, Bullom, Temne, Vai, and Kru, shaped the trajectories of men and women's enslavement before arriving to the Carolinas and the Chesapeake regions. The complexity of captives cultural and ethnolinguistic backgrounds is reflected in diasporic communities such as the Gullah Geechee, descendants of enslaved captives from West and Central Africa who still reside in the lower Atlatnic states. Scholarship of historians such as Marcus Rediker and Vincent Brown highlight the centrality of Africa polities to the development of Atlantic warefare, enslaved resistance, and European Atlatic Empires. Witin the colonial North American press, printers also included articles and advertisements that highlighted enslaved people's methods of everyday resistance such as escape, work slowdowns, sabotage, and community cultivation. However, the language used to describe these facets of enslaved resistance are generally excluded from textual data examined in this project—but it is crucial to keep in mind that methods of black political violence and enslaved resistance in the eighteenth century were never mutually exclusive. In addition, I employ the term *black* within this study in the same vein as scholars such as Jennifer Morgan and Katherine Mckittrick, who use the term to refer not only to people from Africa and their descendants, but also to reflect the idea of the Black Atlantic. Both Morgan and Mckittrick's scholarship explore how contested conceptions of historic blackness emerged in the early modern Atlantic, charting new historiographic paths forward for the study of racial slavery and black diasporic experience.

As a case study, this project engages with contemporary discussions at the forefront of interdisciplinary scholarship at the intersections between studies of early modern slavery, enslaved resistance, colonialism, race, and capitalism and digital history, digital humanities (particularly critical black DH), and data science. However, as an experiment it remains hyper-focussed on the possibilities of close historical contextualization of even the smallest patterns that emerge through computational inquiry.

---

## Why Digital History? What can text data show us?
#### Co-Occurrence of Nouns and Adjectives in Corpus One 1732-1742
![image](https://github.com/user-attachments/assets/6dc422c1-5349-466a-901c-0897810f0df8)

*Note: The legend on the right labelled “cooc” stands for the number of co-occurrences. This word co-occurrence network displays th most frequent noun and adjective co-occurrences in the first ten years of the South Carolina Gazette’s publication included in Corpus One. On the bottom of the network visualization, we can see the co-occurrence of the terms “rebellious” and “negroes.”*

Digital methods, such as text mining for historical analysis, are central to this research, offering insights into linguistic structures and patterns that traditional historical modes of investigation, such as close reading and contextualization, alone do not easily uncover. The colonial press printed and disseminated texts shaped by the social, cultural, and political priorities of white colonists, ship captains, merchants, enslavers, and administrators from numerous locales throughout the British Empire. These priorities influenced the content of what was published and the linguistic framing of black resistance. While traditional historical methods excel at interpreting individual narratives, they can fall short in identifying the broader structural patterns embedded in language over time.

Text mining techniques, including word frequency analysis and part-of-speech co-occurrence, allow us to pinpoint moments when colonial authors and printers differentiated between perceptions of when black conspirators could remain “our slaves” and when they could only be “the rebellious Negroes.” These linguistic shifts reflect how black resistance shaped white authors to rationalizations of their dependence on enslaved labor with the destabilizing force of black defiance. By aggregating and analyzing data systematically, digital methods expose traces of black political violence embedded within colonial language, enabling us to read against the grain of the texts. Moreover, digital methods afford further insights into temporal, regional, and colonial change. Regional variations, such as tactical selectivity of information and reticent vocabularies, underscore how local contexts influenced the colonial descriptions of collective enslaved resistance, while shared linguistic strategies—such as the pervasive use of passive voice—reflect broader white anxieties.

#### Example of the Output of a Concordance Search for the Term "Insurrection" in Corpus One (The *South Carolina Gazette*)
![image](https://github.com/user-attachments/assets/ce57527a-f615-43af-8c7b-de7549aedd18)

*Note: Concordances are a computational technique that allows researchers to view all instances of a given word, token, lemma, or phrase and its surrounding textual context.*

Importantly, digital methods highlight that even within articles that expressed reluctance or unease about slavery and the treatment of enslaved men and women, white authors employed similar grammatical structures that reinforced and flattened ideas of black collective resistance. This suggests that these linguistic patterns undergirded the ideological stances of individual writers, pointing to a shared colonial grammar that could, at an operational level, transcend editorial intent and reinforce the broader racial and social orders set in motion by the transatlantic slave trade. 

#### Distribution of Syntactic Dependency Relationships for Target Lemmas in Corpus One 1732-1775
![Screenshot 2024-11-17 191434](https://github.com/user-attachments/assets/16ce3a14-5372-41e6-8792-4e0b494a82c8)

*Note: This grouping of visualizations displays the relative frequency of specific syntactic dependency relationships (dependency grammars) for the lemmas “insurrection,” “negro,” “negroes,” “rebel,” “rebellious,” and “slave” in Corpus One between 1732 and 1749. The legend on the right labelled “dep_rel” stands for dependency relation. Each type of dependency relation, based on the Universal Dependencies annotation scheme, is color coded. Notably, between the 1730s the lemma “negroes” more frequently appeared in sentences as the syntactic object or oblique nominal. By the 1740s, “negroes” was more often employed as a nominal modifier, meaning that it modified another noun.*

By scaling up the analysis of linguistic patterns, digital methods provide a comprehensive view of how language functioned as both a tool of colonial power and a record of disruption. This approach highlights structures of oppression and recovers the traces of black defiance that reshaped those structures. Digital analysis, therefore, opens new avenues for understanding the dynamic relationship between the structure of language, power, and historical black resistance. Thus, when employed carefully and creatively, computational methods can open novel avenues for understanding the dynamic relationship between language, power, and resistance.

#### Percentage of Active and Passive Voice in Corpus One 1732-1775
![image](https://github.com/user-attachments/assets/f440a6c1-9426-4388-92a3-98e0d68ed17f)

*Note: This figure highlights the percentage of active and passive voice sentences in Corpus One (1732-1775). For Corpus One, Corpus Two, and Corpus Three, the percentage of passive voice and active voice follow similar distributions.*   

#### Percentage of Active and Passive Voice in Corpus Two 1736-1775
 ![image](https://github.com/user-attachments/assets/6a15426e-2a4c-44bf-9959-a63ef00fbed9)

*Note: Percentage of active and passive voice sentences in Corpus Two (1736-1775). A little over sixty percent (61.3%) of the sentences in the articles related to enslaved resistance published in the Virginia Gazette feature active voice, while just under forty percent (38.7%) contain passive voice.*

This project underscores the the idea that digital methods provide an essential avenue for re-examining well-trodden archival sources - in particular those authored by oppressors, enslavers, and colonizers. By looking beyond narrative content, we can uncover the deeper ideological work performed by language—work that sought to flatten and distort enslaved resistance to fit colonial prerogatives. Understanding how language was used to diagnose and contain black resistance in the past equips us to critically engage with the persistence of these dynamics in contemporary narratives about race and resistance.

#### Pronoun Usage per 10,000 words in Corpus One 1732-1773
![image](https://github.com/user-attachments/assets/29a3fc5d-ba2a-4122-a962-bacde6176d01)

*Note: This figure illustrates the normalized usage of pronouns over the eighteenth century in Corpus One (*South Carolina Gazette*). The pronoun frequencies are relativized per 10,000 words to better address varying article lengths and years with relatively little text data. The distribution of pronoun frequencies reflects patterns text data over time, highlighting that in the 1750s the South Carolina Gazette printed little information regarding collective enslaved resistance after 1750.* 

#### Pronoun Usage per 10,000 words in Corpus Two 1736-1775
![image](https://github.com/user-attachments/assets/c13b2295-45c7-4cfe-9e4e-0a85c7e7fdda)

*Note: This figure highlights the normalized usage of pronouns over the eighteenth century in Corpus Two (*Virginia Gazette*). The pronoun frequencies are relativized per 10,000 words to better address varying article lengths and years with relatively little text data. The distribution of pronoun frequencies generally reflects patterns in text data over time, highlighting that in the 1740s and 1750s the *Virginia Gazette* published relatively little information regarding collective enslaved resistance.* 

As a preliminary case study, this project advances the idea that colonial grammar was iteratively deployed to rationalize and contain perceptions of black resistance, embedding it into the fabric of the colonial worldview. By analyzing these linguistic patterns at scale, my research reveals how language reduced the complexity of collective black resistance into a distorted and flattened phenomenon. This work reminds us that the iterative nature of language can obscure as much as it reveals, perpetuating power structures while shaping historical narratives.

Baldwin reminds us that “language reveals the speaker.” The colonial newspapers I analyze reveal linguistic strategies designed to erase the complexity of black resistance and justify its containment as well as the perpetuation of racial slavery. In doing so, my thesis does not recover lost voices but instead exposes the mechanisms that sought to silence them.

### Overview of the Transatlantic and Intercolonial Slave Trades to South Carolina and Virginia alongside Reports Refercing Collective Enslaved Resistance printed in the *South Carolina Gazette* and *Virginia Gazette* in the Eighteenth Century
Below, I generated two rudimentary maps that display general embarkation regions of transatlantic and intercolonial voyages weighted by the number of enslaved captives that arrived in South Carolinia and Virginia ports and the locations referenced in the *South Carolina Gazette* and *Virginia Gazette*'s reports regarding collective enslaved resistance. These maps can be re-created by following the University of California, Santa Cruz (UCSC) guide's for mapping data from [SlaveVoyages.org](https://www.slavevoyages.org/). To find the general guide for generating a map in QGIS see [Mapping Data from SlaveVoyages.org](https://guides.library.ucsc.edu/DS/Resources/Class-Specific/LALS194E/MappingData). For creating a heatmap and displaying basic change over time with [QGIS software](https://www.qgis.org/) (Quantum Geographic Information System) see the [Heatmaps and Change over Time](https://guides.library.ucsc.edu/DS/Resources/Class-Specific/LALS194E/Heatmaps) tutorial. These tutorials come from UCSC's course [LALS 194E - Unfree Migrations](https://guides.library.ucsc.edu/DS/Resources/Class-Specific/LALS194). I adapted these guides to meet my project's objectives, including adding layers that could display the referenced locations from the colonial press. Moreover, these maps are only starting points—it is critical bear in mind that they dispay in a disarmingly whimsical manner, the violent and obscene trafficking of people from Africa and their descendants during the eighteenth century. Moreover, the data displayed should not be taken as complete or wholly representative of the scale of human trafficking during this period. Remember: data are people.

What these maps do afford is a unique perspective on the forced migrations of enslaved captives alongside when and where news regarding collective enslaved resistance was printed in the *South Carolina Gazette* and *Virginia Gazette.*

#### Map of Transatlantic and Intercolonial Embarkation Locations for Voyages that Disembarked in South Carolina and the Referenced Locations of Collective Enslaved Resistance Printed in the *South Carolina Gazette* between 1732 and 1775
![SouthCarolina_static_BlankBaseMap](https://github.com/user-attachments/assets/b14b7833-d4e1-4e41-8f51-43ad34ca81d2)

This map illustrates the violent trafficking of people from Africa and their descendants to the British North American colony of South Carolina between 1732 and 1775. The base map for this visualization and the following is a map do not display country borders or regions. This basemap as well as many others are freely available through the [Natural Earth Vector GitHub repository](https://github.com/nvkelso/natural-earth-vector). I have opted for a base map without country borders or regional divisions in order to not reinforce inaccurate representations colonial and postcolonial boundaries; the resourse [African Regions](https://www.africanregions.org/) provides a useful frame of reference and discussion from seminal digital humanists, offering a window into recent scholarship on the social, historical, and cultural complexities of spatial mapping and historical data. It is important to note that this map currently solely displays data by year because the data for specific dates that voyages began and ended are often incomplete (this is especially true of data regarding the date of enslaved captives purchase and embarkation from Africa and other Atlantic colonies). Using a heatmap, this map displays extant locations of [transatlantic](https://www.slavevoyages.org/voyages/kWfksL9o) and [intercolonial](https://www.slavevoyages.org/voyages/dU1QsMYL) embarkation regions derived from the Slave Voyages database. The heatmap is weighted by the number of transatlantic and intercolonial voyages that embarked for ports in South Carolina, namely Charleston. This means that the lighter the visualization becomes (yellow) the greater the number of voyages concentrated in that area and the darker (purple) the fewer voyages. The red star markers highlight the locations mentioned in the *South Carolina Gazette*'s coverage of news related to enslaved resistance—including reports of occurred insurrections, conspiracy scares, legislation, editorials, news of rebels (both enslaved and self-liberated black communities), and shipboard uprisings. This map was generated using QGIS, the free and open-source counterpart to ArcGIS. 

#### Map of Transatlantic and Intercolonial Embarkation Locations for Voyages that Disembarked in Virginia and the Referenced Locations of Collective Enslaved Resistance Printed in the *Virginia Gazette* between 1736 and 1775
![Virginia_Static_BlankBaseMap](https://github.com/user-attachments/assets/40595f13-3b23-464e-8f1a-ef035e0f85f8)

This map illustrates the violent trafficking of people from Africa and their descendants to the British North American colony of Virginia between 1736 and 1775. It is important to note that this map currently solely displays data by year because the data for specific dates that voyages began and ended are often incomplete (this is especially true of data regarding the date of enslaved captives purchase and embarkation from Africa and other Atlantic colonies). Using a heatmap, this map displays extant locations of [transatlantic](https://www.slavevoyages.org/voyages/qYCan1Ao) and [intercolonial](https://www.slavevoyages.org/voyages/xMxYCnNz) embarkation regions derived from the Slave Voyages database. This map displays the same variables as the previous.

### Computational Methods
Through methods of text mining for historical analysis, the computational research produced in this project primarily focused on linguistic features such as collocations, context-dependent pairings of words that frequently occur together; concordances, a tool for viewing all instances of a given word or phrase and its surrounding context; part of speech co-occurrence; the frequency of passive voice constructions; and syntactic dependency relationships, which refer to the grammatical relations between words in a sentence. In particular, this study focused continuities and discontinuties in part of speech co-occurrence, such as pronouns and adjectives or nouns, and diachronic rates of passive and active voice constructions. The greatest challenge to employing these methods to explore the rhetoric of collective enslaved resistance published in the *South Carolina Gazette* and *Virginia Gazette* is the fact that both newspapers published relatively few total words on the topic—a product of doing business in Lowcountry and Chesapeake in the eighteenth century. It is for this reason that this study does not employ digital methods such as word embeddings, which enables computers to represent words as numbers that can produce abstract conceptions of word similarity over time, or statistical measurements of significance. Thus, as a case study this project primarily illustrates the fine-grained ways in which historians working with relatively small amounts of historic data can still appropriately and productively enage with digital methods to ask new questions about the past. 

---

## Data & Corpora
To transform the rhetoric of collective enslaved resistance published in the *South Carolina Gazette* and *Virginia Gazette* into computationally accessible data, I designed and generated a corpus, meaning a collection of text basic supplemental metadata, for each publication. The first dataset, called Corpus One, contains 18,060 words published across forty-five articles in the *South Carolina Gazette* between the 1730s and the 1770s that reference varying forms of collective enslaved resistance. The second dataset, called Corpus Two, contains 24,044 words and metadata for fifty-six articles related to enslaved resistance published in the *Virginia Gazette* during the same time frame. Notably, beginning in 1766, Corpus Two contains some duplicate reports because there were multiple outlets called the *Virginia Gazette* that were published in Williamsburg.  To include as much text data as possible from Williamsburg’s press, Corpus Two contains text, including the same reprinted accounts, from three of the *Virginia Gazette* newspapers. While I primarily refer to the *Virginia Gazette* in the singular, throughout both chapters I am careful to attend to the differences between these publications.
To find all extant references to collective enslaved resistance in both publications, I used keyword searches in History Commons digitized and transcribed online collections of the South Carolina Gazette and *Virginia Gazette*.  For both publications I used close readings of both publications to inform Boolean operational searches for permutations of terms and phrases including words such as “insurrection,” “slave,” “negro,” “conspiracy,” “rebel,” “plot,” “wicked,” “attempt,” “massacre,” “discover,” “horrid,” “revolt,” “uprising,” and “instigate.” In addition to keyword searches, I cross-referenced primary sources, such as *Lloyd’s List*, legal codes, and slave trade data, as well as secondary scholarship to validate and supplement my manual collection process. Thus, in generating Corpus One and Corpus Two, I endeavored to capture as much of the colonial rhetoric of collective enslaved resistance as I could within the constraints of what has been digitized. 
For the purposes of content analysis I created a tertiary dataset called Corpus Three that contains 91,746 words across 320 articles, published in both the *South Carolina Gazette* and *Virginia Gazette* between 1732 and 1775. Corpus Three contains up to ten articles from every year between 1732 and 1775, meaning that for years where both publications printed less than ten articles combined featuring target words, such as “rebellious,” “rebels,” “conspiracy,” “plot,” “insurrection,” or “revolt,” I included all extant articles from that year. 

---

## Computational Tools and Data/Archival Resources
### R and Rstudio
The code for this project was written in [R](https://www.r-project.org/), an open-source programming lagnuage designed for data analysis and statstical computing, and compiled in [Rstudio](https://posit.co/download/rstudio-desktop/), an open-source integrated development environment that (IDE) that allows for better interfacing with R. Like popular programming languages like Python, R has great utility for computational text mining—as it has numerous libraries that faciliate text data exploration, experimentation, and visualization. While R is not as general purpose as other programming languages (Python, Java, C++, etc.), it has a lower barrier to entry for interdisciplinary scholars and novice coders like myself. For historians and digital humanists alike looking to learn data science techniques in R or Python, the free online resource [Coding the Past](https://www.codingthepast.com/) offers numerous intructory, intermediate, and advanced tutorials based in historical methods and data. In addition, resources such as the [Programming Historian](https://programminghistorian.org/en/lessons/) offer more advanced programming lessons that explore topics such as distant reading techniques, mapping, and network analysis. 

### Databases
The cited primary sources and data created for this project are derived from the following online databases: 
- I manually derived the text data for the *South Carolina Gazette* and the *Virginia Gazette* from [History Commons](https://history-commons-net.colorado.idm.oclc.org/) online collections of both publications which have been scanned and digitized. These data can be found in the folders for Corpus One and Corpus Two.
- For transatlantic and intercolonial (or intra-American) slave trade data I used [SlaveVoyages.org](https://www.slavevoyages.org/)
- For eighteenth century anti-slavery legislation I employed the digital reference archive, [U.S. Anti-Slavery Laws Archive](https://usantislaverylaws.org/public/index.php), that I created with Dr. Henry Lovejoy in collaboration with the University of Colorado Boulder's [Digital Slavery Research Lab](https://www.colorado.edu/lab/dsrl/), and with technical support from the team at [Walk With Web](https://walkwithweb.org/Public/) in the summer of 2023. This digital reference archive contains primary source documents based on the legislation collected in appendices A and B in W.E.B. Du Bois, *The Suppression of the African Slave-Trade to the United States of America, 1638–1870*, originally published in 1896. This archive, which retraces W.E.B. DuBois' thesis at Harvard, hosts over 300 pieces of anti-slavery legislation enacted in the Thirteen Colonies and United States since the 1600s.
- For colonial newspapers outside of the *South Carolina Gazette*, *Virginia Gazette*, and *Pennsylvania Gazette* I used the database [America's Historical Newspapers](https://infoweb-newsbank-com.colorado.idm.oclc.org/apps/readex/?p=EANX) hosted by Readex.

### Useful R Libraries and External Tools
#### External Tools
- PassivePy: a python and spacy based transparent tool developed by Amir Sepehri, Mitra Sadat Mirshafiee, and David M. Markowitz to automatically detect passive voice. [PassivePy](https://github.com/mitramir55/PassivePy), which also has a [streamlit application](https://passivepy.streamlit.app/), enables researches to automatically detect passive voice constructions in both large and small text data, making it a versatile and flexible tool for examining English language text data (inclduing historical).
- Sketch Engine: [Sketch Engine](https://www.sketchengine.eu/) is an online computational corpus linguistics platform that supports a wide variety of tools for examining language. The primary draw back of this platform is that it is subscription based.
  
#### Basic Utility Libraries in R
- `lubridate`: for working with dates and times
- `tidyverse`: provides general data and text analysis utility

#### Loading Data Libraries in R
- `readxl`: loads excel worksheets into Rstudio environment as object (dataset)
- I also made extensive use of R's base capability for reading csv files into the environment

#### Useful Text Mining (many of these overlap in functionality and dependencies) Libraries in R
- `udpipe`: this package provides access to natural language processing techniques such as tokenizing, tagging, lemmatization, and dependency parsing
- `tm`: faciliates easier creation and inspection of textual corpora
- `stringr`: helps to work with and manipulate strings
- `NLP`: a natural language processing library
- `tokenizers`: a tool for easily tokenizing text into machine readable components
- `stringi`: a useful pattern searching/detection tool that allows for the use of regular expressions
- `quanteda`: works with text data and has a built in concordance feature
- `textstem`: performs lemmatization and stemming
- `tidytext`: facilitates conversion of data into tidy formats

#### Visualization Libraries in R
- `ggplot2`: provides access to versatile graphic visualizations and customization
- `ggraph`: an extension of ggplot that enables a more flexible framework for visualizing networks using layers
- `igraph`: for network analysis and visualization

#### Visualization Aesthetics Libraries in R
- `extrafont`: allows access to large libary of fonts for designing visualizations
- `svglite`: enables visualizations to be exported as .svg files to maintain quality when resizing
- `ggrepel`: for graphing aesthetics with word

#### A Note on Replicating Results and Code
I have attempted to thoroughly annotate and document my code in the RMD files stored within this repository for each corpus. Each code chunk has an explanatory title and other necessary information regarding the code. However, for more complex coding skills, such as adapting the functions I wrote for tokenizing text or appending year information, please consult outside resources to ensure that any code replicated or adapted meets desired requirements. Keep in mind that this code was designed for working with small amounts of historic text data and thus is a specific use-case. 

---

## Licenses
Creative Commons Attribution 4.0 International (CC BY 4.0)

## AI Contribution Acknowledgment for GitHub Pages Site
This project includes code and text partially generated with the assistance of OpenAI's ChatGPT for generating Markdown and HTML code in designing the GitHub pages project website. The use of AI-generated content is licensed under the same terms as the rest of the repository.

---

## Author
Chloe A. Zehr (she/they)

B.A., History, University of California, Santa Barbara, 2021

M.A., History, University of Colorado Boulder, 2024

Contact: Chloe.Zehr@colorado.edu & chloeazehr@gmail.com

---

## Acknowledgements
I am beyond grateful for and indebted to the expertise, unwavering support, and feedback from the following scholars and interdisciplinary labs at the University of Colorado Boulder who helped me develop and revise this project: 
- Dr. Honor Sachs (project advisor) at the University of Colorado Boulder
- Dr. Ashleigh Lawrence-Sanders (History) at the University of Colorado Boulder
- Dr. Henry Lovejoy (History) at the University of Colorado Boulder
- Dr. David Glimp (English) at the University of Colorado Boulder
- Dr. Susan Brown (Linguistics) at the University of Colorado Boulder
- The [Digital Slavery Research Lab](https://www.colorado.edu/lab/dsrl/) at the University of Colorado Boulder
- The [Center for Research Data & Digital Scholarship](https://www.colorado.edu/crdds/) at the University of Colorado Boulder
- The faculty and advisors for the [Digital Humanities Certificate](https://www.colorado.edu/crdds/dhgc) program at the University of Colorado Boulder

---

## Additional Scholarship
- Jo Guldi, *The Dangerous Art of Text Mining: A Methodology for Digital History* (Cambridge University Press, 2023)
- Jennifer L. Morgan, *Reckoning with Slavery: Gender, Kinship, and Capitalism in the Early Black Atlantic* (Duke University Press, 2021)
- David Eltis, *The Rise of African Slavery in the Americas* (Cambridge: Cambridge University Press, 1999)
- Robert G. Parkinson, *The Common Cause: Creating Race and Nation in the American Revolution* (University of North Carolina Press, 2016)
- Robert Nowatzki, “From Datum to Databases: Digital Humanities, Slavery, and Archival Reparations,” The American Archivist 83, no. 2 (March 8, 2021): 429–48
- David A. Copeland, Colonial American Newspapers: Character and Content (Newark: University of Delaware Press, 1997)
- Jason T. Sharples, *The World That Fear Made: Slave Revolts and Conspiracy Scares in Early America* (Philadelphia: University of Pennsylvania Press, 2020)
- Vincent Brown, *Tacky’s Revolt: The Story of an Atlantic Slave War* (Cambridge, Massachusetts: The Belknap Press of Harvard University Press, 2020)
- Stephanie Smallwood, *Saltwater Slavery: A Middle Passage from Africa to American Diaspora* (Cambridge, MA: Harvard University Press, 2007)
- For contemporary scholarship at the intersections of data and slavery see the [Journal of Slavery and Data Preservation](https://jsdp.enslaved.org/)
- For recent conversations regarding redefining African regions the resource [African Regions](https://www.africanregions.org/index.php) offers useful maps as well as historiographical context.
