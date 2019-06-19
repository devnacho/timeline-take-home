# Timeline Take Home Challenge

We are a very pragmatic team at Timeline and this extends to the way that we work with you to find out if this team is a great fit for you. So instead of coding at a whiteboard with someone watching over your shoulder under high pressure, which is not a thing we often do, we instead discuss code that you have written previously when we meet.

This can be a project of your own or a substantial pull request on a third party project, but some folks have done largely private or proprietary work, and this engineering challenge is for you.

## What we are looking for?

Keep it simple. Really. 2-4 hours isn't a lot of time and we really don't want you spending too much more time on it than that. It's more important for us to see how you approach the problem rather then solving it in its entirety.

Treat it like production code. That is, develop your software in the same way that you would for any code that is intended to be deployed to production. For example, if you would usually write tests for your code then you should aim to do the same here. These may be toy exercises, but we really would like to get an idea of how you build code on a day-to-day basis.

You can use any language, tools or solutions as you see fit. 

You can submit the code in any way that is convenient for you - you can email us a tarball, a pointer to download your code from somewhere or just a pointer to a source control repository. In your submission, you should include:

- The code and what ever is required to run it. You can assume that this will run on some *nix like operating system and will have a fairly standard set of command line tools. If you require something specific, either include it inline, or document it in a way that it would be trivial for us to get and run your code.

- A small README documenting the problem you are undertaking; documentation of any assumptions or simplifications you have made; and a short description of how to run your code.

# Challenge

## Option 1: Portfolio Performance Challenge

### Requirements:

- As a User I want a web application where I can enter the state of my portfolio of assets some day in the past and see how much money would be worth today.

#### Example: 
- Start Date: 2013-03-20
- Initial Balance: $32500
- Portfolio Allocation:
  - AAPL: 20%
  - GOOG: 50%
  - VTI: 30%
  
Please make a small app where the user can enter this data and can get the results. Feel free to visualize the output as you see fit (Aggregate portfolio returns chart, Portfolio Allocation evolution over time, etc). 

To obtain the historical returns you can use this free API https://www.worldtradingdata.com/

- Please try to show your skills both on the back-end and in the front-end.
- For styles feel free to use something like normalize.css and if you want a minimal css framework. Writing your own styles is appreciated.
- If you add charts, use any charting library you prefer.

## Optional (Hard Mode): 

If you want to spice things up you can try doing the following things:

- Let the user choose a rebalance frequency (at the end of each month or at the end of each year) where the portfolio is rebalanced to the original allocation. This means that assets with a higher allocation than the initial one have to be sold to buy assets that are below the initial allocation.

- Save the inputs in a Database and generate a URL where the user can enter and retrieve his input.


## Option 2: Your Own Project

Guidelines:

- The project should be of at least 4 hours worth of effort.

- It should be something we can compile / run.

- It should be something you are comfortable discussing.

- It should have a reasonably obvious purpose / use. At least something that you could explain to us in a couple of paragraphs of text (with the assumption you are explaining to experienced engineers).

- It is something that has primarily been worked on by you.

To submit:

- Your code.

- If it is a larger project, a pointer to the most interesting parts that we can review and run.

- A couple of paragraph description of what the code is/does.

