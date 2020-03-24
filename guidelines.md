# Guidelines

## Structuting your Readme
Include the following items:

* Description of the application.
* Relevant commands to manage and run the application(s). 
* Link to the final, hosted application.
* Reasoning behind your technical choices, including architectural trade-offs
    you might have made, anything you left out, or what you might do differently
    if you were to spend additional time on the project.
* Link to other code you're particularly proud of.
* Link to your resume or public profile.

## Application Build

Your front end build should a single page app with a single `index.html`
linking to external JS/CSS/etc. 

## Host It

Host your application build somewhere (e.g. on S3, EC2, Heroku, Google AppEngine, etc.).

## How Will We Review?

Your application will be reviewed by at least three of our engineers. We do take
into consideration your experience level.

### Quality over feature-completeness
It is fine to leave things aside provided you call them out in your project's README. The goal of this code
sample is to help us identify what you consider production-ready code. You
should consider this code ready for final review with your colleague, i.e. this
would be the last step before deploying to production.

### Areas of Assessment 

* **Architecture**: how clean is the separation and construction of the
    application?
* **Clarity**: does the README clearly and concisely explains the problem and
    solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything
    missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?
    Are there any code smells or other red flags? Does object-oriented code
    follows principles such as the single responsibility principle? Is the
    coding style consistent with the language's guidelines? Is it consistent
    throughout the codebase?
* **Testing**: how thorough are the automated tests? Will they be difficult to
    change if the requirements of the application were to change? Are there some
    unit and some integration tests?
	  * We're not looking for full coverage (given time constraint) but just
              trying to get a feel for your testing skills.
* **UX**: is the web interface understandable and pleasing to use?
* **Technical choices**: do choices of libraries, architecture etc. seem
    appropriate for the chosen application?

### Bonus (optional):

* **Scalability**: Explain how your technical choices scale well. If not, is there a
    discussion of those choices in the README?
* **Production-readiness**: does the code include monitoring? Logging? Proper
    error handling?

Please organize, design, test, document and deploy your code as if it were going
into production, then send us a link to the hosted repository (e.g. Github,
Bitbucket...).