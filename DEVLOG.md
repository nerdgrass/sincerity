# Dev Log
The purpose of this document is to record the non-code aspects of this project in a linear form, as well as offer a visible place for me to journal my thoughts &amp; process. If you're wondering how I approach product & web development, here's a history of this repo, from first commit up to present. 

### 9/19/2017 - planning, &amp; research
Created repo, now thinking about structure. Added devlog for inline troubleshooting. Current working idea: Use Gatsby.js to easily and quickly create & deploy company-specific portfolios for extra flourish when pitching potential clients or applying to jobs. I should add that to the readme. 

Okay, done. Onto basic product thoughts! 

The intended users of this application are like myself: time-strapped developers & designers looking for work.

The problem this tool will help solve: To maximize impact of a proposal, whether a f/t job application or a freelance gig, one needs to customize their proposal for the specific client. This is very common advice with resumes; they should ideally be tweaked to every potential employer's needs. But with portfolios, that's a lot more work, so its not commonly done, which leads to even /more/ potential impact by customizing your portfolio, but the cost of that is even more time sunk into an already arduous and long job hunt.

Problem context: Most portfolios are just static websites - relatively lightweight documents w/ multimedia content, usually just text and images. Static site generators strip down this process to templates, themes, and content. These abstractions open up the possibility of CMSs managing the content & static site generator functions (relatively small API - designed to be run on CLI anyways).

Proposed solution: Using a static site generator, collected content, basic templates, and customizable themes, create an interface that allows users to customize their portfolio for specific proposals easily.