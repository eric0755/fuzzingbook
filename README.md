
# About this Book

__Welcome to "Generating Software Tests"!__ 
Software has bugs, and catching bugs can involve lots of effort.  This book addresses this problem by _automating_ software testing, specifically by _generating tests automatically_.  Recent years have seen the development of novel techniques that lead to dramatic improvements in test generation and software testing.  They now are mature enough to be assembled in a book – even with executable code. 

## A Textbook for Paper, Screen, and Keyboard

You can use this book in three ways:

* You can __read chapters in your browser__.  Check out the list of chapters in the menu above, or start right away with the 
<a href="https://www.fuzzingbook.org/html/Intro_Testing.html">introduction to testing</a> or the
<a href="https://www.fuzzingbook.org/html/Fuzzer.html">introduction to fuzzing</a>.  All code is available for download.

* You can __interact with chapters as Jupyter Notebooks__ (beta).  This allows you edit and extend the code, experimenting _live in your browser._  Just click on "Resources $\rightarrow$ Edit as Notebook" at the top of each chapter. <a href="https://mybinder.org/v2/gh/uds-se/fuzzingbook/master?filepath=notebooks/Fuzzer.ipynb" target=_blank>Try interacting with the introduction to fuzzing.</a>

* You can __present chapters as slides__ (beta).  This allows for presenting the material in lectures.  Just click on "Resources $\rightarrow$ View slides" at the top of each chapter. <a href="https://www.fuzzingbook.org/slides/Fuzzer.slides.html" target=_blank>Try viewing slides on the introduction to fuzzing.</a>

## Who this Book is for

This work is designed as a _textbook_ for a course in software testing; as _supplementary material_ in a software testing or software engineering course; and as a _resource for software developers_. We cover random fuzzing, mutation-based fuzzing, grammar-based test generation, symbolic testing, and much more, illustrating all techniques with code examples that you can try out yourself.

## News

This book is _work in progress,_ with new chapters coming out every week.  To get notified when a new chapter comes out, <a href="https://twitter.com/FuzzingBook?ref_src=twsrc%5Etfw" data-show-count="false">follow us on Twitter</a>.

<a class="twitter-timeline" data-width="500" data-chrome="noheader nofooter noborders transparent" data-link-color="#A93226" data-align="center" href="https://twitter.com/FuzzingBook?ref_src=twsrc%5Etfw">News from @FuzzingBook</a> 


## About the Authors

This book is written by _Andreas Zeller, Rahul Gopinath, Marcel Böhme, Gordon Fraser, and Christian Holler_.  All of us are long-standing experts in software testing and test generation; and we have written or contributed to some of the most important test generators and fuzzers on the planet.  As an example, if you are reading this in a Firefox, Chrome, or Edge Web browser, you can do so safely partly because of us, as _the very techniques listed in this book have found more than 2,600 bugs in their JavaScript interpreters so far._  We are happy to share our expertise and making it accessible to the public.

## Frequently Asked Questions

### Technical Issues

#### The interactive notebook does not work!

The interactive notebook uses the [mybinder.org](https://mybinder.org) service, which runs notebooks on their own servers.  There is a [limit of 100 concurrent users for a repository](https://mybinder.readthedocs.io/en/latest/user-guidelines.html).  Also, as listed on the [mybinder.org status and reliability page](https://mybinder.readthedocs.io/en/latest/reliability.html),

> As mybinder.org is a research pilot project, the main goal for the project is to understand usage patterns and workloads for future project evolution. While we strive for site reliability and availability, we want our users to understand the intent of this service is research and we offer no guarantees of its performance in mission critical uses.
    
If mybinder.org does not match your needs, [install jupyter notebook on your machine](https://www.dataquest.io/blog/jupyter-notebook-tutorial/) and clone the project repository [from the Github project page](https://github.com/uds-se/fuzzingbook).  Go to the `notebooks/` folder, where you can then open, edit, and run all notebooks at your leisure.

#### Why does it take so long to start an interactive notebook?

Starting Jupyter through mybinder.org normally takes about 30 seconds, depending on your Internet connection. If, however, you are the first to invoke binder after a book update, binder recreates its environment, which will take a few minutes.  Reload the page occasionally.

#### Do you provide PDFs of your material?

At this point, we do not provide support for PDF versions.  We will be producing PDF and paper versions once the book is complete.

### Content

#### Which content will be coming up?

The contents of this book will include topics such as:

1. Introduction to Testing
2. Basic Fuzzing
3. Coverage
4. Mutation-Based Fuzzing
5. Fuzzing with Grammars
6. Efficient Grammar Fuzzing
7. Grammar Coverage
8. Configuration Fuzzing
9. Parsing and Mutating Inputs
10. Probabilistic Testing
11. Reducing Failure-Inducing Inputs
12. Fuzzing Function Calls
13. Fuzzing User Interfaces
14. Search-Based Testing
15. Symbolic Testing
16. Mining Grammars
17. Fuzzing and Invariants
18. Protection and Repair

See the table of contents in the menu above for those chapters that are already done.

#### How do I cite your work?

Thanks for referring to our work!  Once the book is complete, you will be able to cite it in the traditional way.  In the meantime, just click on the "cite" button at the bottom of the Web page for each chapter to get a citation entry.

### Other Issues

#### I have a question, comment, or a suggestion.  What do I do?

You can [tweet to @fuzzingbook on Twitter](https://twitter.com/fuzzingbook), allowing the community of readers to chime in.  For bugs you'd like to get fixed, report an issue on the [development page](https://github.com/uds-se/fuzzingbook/issues).

#### I have reported an issue two weeks ago.  When will it be addressed?

We prioritize issues as follows:

1. Bugs in code published on fuzzingbook.org
2. Bugs in text published on fuzzingbook.org
3. Writing missing chapters
4. Issues in yet unpublished code or text
5. Issues related to development or construction
6. Things marked as "beta"
7. Everything else

#### How can I solve problems myself?

We're glad you ask that.  The [development page](https://github.com/uds-se/fuzzingbook/) has all sources and some supplementary material.  Pull requests that fix issues are very welcome.

#### How can I contribute?

Again, we're glad you're here!  See our [Guide for Authors](Guide_for_Authors.ipynb) for instructions on coding and writing.
