# Latex Template for Research Proposals
This LaTeX template can be used to draft and outline the topic for a academic paper or thesis in Computer Science (in English and German language). 
I have found it particular helpful for topics that are more on the engineering side of CS.

## Table of Contents
1. [Core Ideas and Concept](#Concept)
2. [How to fill in the Template?!](#FillInTemplate)
3. [PDF generation Tool Chain](#ToolChain)
4. [Setup LaTeX Environment from Scretch](#SetupFromScratch)
5. [Credits](#Credits)

## <a name="Concept"></a> Core Ideas and Concept
Students at the Computer Science department of [University of Applied Sciences Darmstadt](https://www.fbi.h-da.de/fbi.html "Hochschule Darmstadt, University of Applied Sciences") frequently have to write seminar papers. 
In addition, they have craft a comprehensive thesis (Bachelor's Thesis or Master's Thesis, depending on the degree they aim for) at the end of their studies. 
During the creation of these papers (or theses), one of the major challenges for many students is to find the topic they are going to write about and shape it the way that it is interesting and of relevance.

The purpose of this template is to support students in developing and defining the essence of what they want to write their academic papers about. 

As a supervisor I ask my students to fill it the template already at the start of their research projects.
It forces them to write down, rethink, and reshape their research ideas.
Based on this document I will discuss their ideas with them, helping them to shape a good storyline and strategy for their work. 

Usually my students create multiple iterations of this documents as they dive deeper and deeper into their area of research and gain deeper understanding of what they want to accomplish.

The most important part for the students, is to have them answer the following four questions (within in the template they are described in much further detail as LaTeX comments):
- __What is the problem you want to address in your work?__
    - The objective here is to have students give a very brief and to the point description (1 sentence) of the problem they want to address within their paper.
- __Why is it a problem?__
    - Why is the problem at all relevant? Why should we spend effort into investigating/solving it?
- __What is the solution you developed in your work?__
    - What results have been (or will be) produced? How do these results address the proposed problem?
- __Why is it a solution?__
    - What is the quality of the results? What shortcomings are there? How did the student ensure that the results are genuine?

Furthermore, I ask them to provide:
- A abstract of their proposed work
- A proposal for a table of contents
- relevant/significant pieces of related work they have already found


## <a name="FillInTemplate"></a> How to fill in the Template?! 
The intention of this template was to be as easily usable as possible. 
Nevertheless, there are a few things to keep in mind while using it. 
The following guide is supposed to assist you in using it as smooth as possible. 


#### Step 0: Clone, Open, and Generate a PDF
Start by cloning or downloading this repository and opening the _researchproposal.tex_ file in your favorite LaTeX environment. 
The template is set up the way that, at this point, you should be able to generate a PDF without any errors or warnings.
This will allow you to double check that your environment is set up the way that you can generate a PDF document from the template. 

In case you have trouble generating the PDF, please take a look to the [PDF generation tool chain](#ToolChain) section.
This may help you getting the PDF generated.


#### Step 1: Choose Language
Please acknowledge that the template is bilingual.
It can be used to create a research proposal in English or in German language. 
Thus, the first thing you have to do is choosing the language that you want to use. 
This is done by opening _researchproposal.tex_ and stating the language in the following comment block.

    % ##########################################
    % # Choose the language for the document
    % # de = German
    % # en = English
    \newcommand{\lang}{en}
    % ##########################################


#### Step 2: Create your Proposal - Fill in your ideas!
Obviously, filling in your content is the most important step. 
In order to do that, you will find a lot of comment blocks in the document that assist you.
These blocks will also give you further explanations about what you need to consider and keep in mind.
This is where you need to fill in your content.

__Important:__ Read and follow the explanations for each comment block!

The following is an example for these blocks: 

    % ##########################################
    % # Include the the title of your paper/thesis here.
    % ###### 
    % Coming up with a good title is hard.
    % It should:
    %  1. capture the contents of the your work
    %  2. not be to broad or generic
    %  3. use established terms and wordings
    %  4. make people curious about your work
    %  5. use current buzzwords if possilbe (but do it right)
    %  6. not use too many buzzwords :-)
    insert title here
    % ##########################################


## <a name="ToolChain"></a> PDF generation Tool Chain
There is nothing special about the tool chain used to generate the pdf. 
It uses:
- pdflatex - to generate a pdf document
- biber - to process the bibliography

Assuming you are familiar with LaTeX it should easily be set up. 



# <a name="SetupFromScratch"></a>How to setup a LaTeX Environment from Scretch?
If you have no LaTeX environment running and want still fill in this template using LaTeX, you may try the following combination of tools - Setup Visual Studio Code as IDE, LaTeX Workshop as extension for VS Code to edit LaTeX, and Tex Live as LaTeX distribution. 

Please understand, if you have a running environment that makes sense for you - stick with it. It is by no means necessary to use the one poposed here. 
Further, there are probably better environments out there. 
However, I personally find this setup highly usable.
This is due to the points that, it is available for all major operating systems, it is light weight, and easy to use. 

If you want to give it a shoot, here is how to set it up:

#### Step 1: Install TeX Live
The [project's website](https://www.tug.org/texlive/ "TeX Live Website") descibes [TeX Live](https://en.wikipedia.org/wiki/TeX_Live "Wikipedia on TeX Live") as: "an easy way to get up and running with the TeX document production system. It provides a comprehensive TeX system with binaries for most flavors of Unix, including GNU/Linux, and also Windows. It includes all the major TeX-related programs, macro packages, and fonts that are free software, including support for many languages around the world."

It is available for all major operating systems. 
You will find how tos for installing it on your machine on the [project's website](https://www.tug.org/texlive/ "TeX Live Website").

I would recommend to go for a full installation, as this may prevent any trouble of missing packages later. 
As an example, as a Fedora user I simply installed the _texlive-scheme-full_ package though _dnf_ (installing all LaTeX packages that TeX Live has to offer)

#### Step 2: Install Visual Studio Code

2. [Visual Studio Code](https://en.wikipedia.org/wiki/Visual_Studio_Code "Wikipedia on VSCode")


#### Step 3: Install the VS Code extension "LaTeX Workshop"




#### Step 4: Setup Tool Chain
3. Install the VS Code Extension called [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop "LaTeX Workshop - Visual Studio Marketplace")



install ___texlive-scheme-full___



Make sure you have a LaTeX distribution installed 
Install Visual Studio Code on your System https://code.visualstudio.com/




## <a name="Credits"></a> Credits
The essence and wisdom of the core of this research proposal is NOT my own. 

It is more the collected wisdom from many people that I have met and talked to. 
Further, I have encountered this style of presenting academic engineering work as a best practice at many well established conferences.

To the best of my knowledge I am just the only one to make it available like that.
