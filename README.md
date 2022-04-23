# Simple Gym Exercise Sheet Converter - From XLSX to TXT for Smartwatch Notes
This repository contains a simple script for a quick conversion of my gym exercises sheets from XLS to TXT, to make the importation on my Apple Watch's Google Keep notes quicker.

Gym is the place where I relax. I prefer not to be distracted from my phone while I’m training, or being afraid of it being stolen.
For this reason I like leaving my phone at home whenever <ins>I can and give my tired eyes a break!</ins>

As a nerd, I don't like having my sheet printed or hand written on a paper. Instead, **I find more comfortable having it always on my wrist** on my smartwatch. <br>
However, since I'm a lazy guy, I don't want to waste my time by copying and pasting all the execercises from an Excel Sheet to a **Google Keep** note every time I make a change to my training sheet: that's the reason that led me to write this simple script.

*Bonus*: I included my new Legs / Push / Pull Hypertrophy Bodybuilding program that I just created.


## Table of Contents
<ol>
	<li>
		<a href="#get-started">Get Started</a>
		<ul>
			<li><a href="#prerequisites">Prerequisites</a></li>
		</ul>
	</li>
	<li><a href="#how-the-script-works">How the Script Works</a></li>
	<li><a href="#script-purpose-and-limitations">Script Purposes and Limitations</a></li>
	<li><a href="#knotes-about-the-included-training-program">Notes About the Included Training Program</a></li>
	<li><a href="#software--used-for-developmento">Software Used for Development</a></li>
	<li><a href="#known-issues">Known Issues</a></li>
</ol>
 
 
## Get Started

The following instructions will allow you to have a working copy of the project on your local machine.

### Prerequisites

Software to install for the project to work, and how to install it.

```
* A Windows, Linux or MacOS machine
* Python 3.7+
* Python Pip3
```

Install the necessary Python Libraries using the following shell command: ```pip install -r requirements.txt```

<p align="right">(<a href="#top">back to top</a>)</p>


## How the Script Works

The script operation is pretty simple and straight forward. The script opens and converts the specified XLSX file, and then copies the resulting txt in your clipboard.

I included some simple customisations:
* Setting for the number of blank lines between each exercise row
* Selection of the bullet list dot type
* Selection of the item list separator

<p align="right">(<a href="#top">back to top</a>)</p>


## Script Purposes and Limitations

**The script is not intended to work on different sheets formats than the one provided.** <br>
You can edit the training days names and increase or reduce their number. However, **you cannot remove or add columns or rename them**.

I wrote this script in my free time because it's really useful for me, and I decided to share it hoping it could be useful to someone.

The script is **shared as a sample** with some simple customisations available. 

<p align="right">(<a href="#top">back to top</a>)</p>


## Notes About the Included Training Program

**I’m not a professional qualified coach**, but just a guy with a passion and years of experience inside gyms. <br>
The included program is tuned for my body and my goals, and its given for free and without any warranties just for the purpose of showing how the conversion script works.

<p align="right">(<a href="#top">back to top</a>)</p>


## Software Used for Development
* [Jupyter Notebook](https://jupyter.org/) - Development platform for the Python language
* [Visual Studio Code](https://code.visualstudio.com/) - IDE used for development and testing

<p align="right">(<a href="#top">back to top</a>)</p>


## Known Issues
No known issues so far!

<p align="right">(<a href="#top">back to top</a>)</p>
