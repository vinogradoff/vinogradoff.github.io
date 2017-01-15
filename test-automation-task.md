### Task
Please automate the following actions as **one** UI Selenium-based test.


### Story
You've just got a job as QA Engineer at Google. Your first work field is to automate end-to-end tests for Google Search service, as the existing tests were altogether gone after the Big Bang Datacenter Crash. Team Lead suggests that ca. 50 user scenarios should be automated by you in the following 5-6 weeks, which means you have about 4 hours for scenario on average. You start with the scenarion below.

### Rules

- Use your favorite programming language (e.g. Java, JavaScript, Python, Ruby, C# or whatever you know best).
- You may use any helping framework if you want to.
- Design it as **one** test, not three, not five. You may have more than one asserts your test.
- Selenium (2.x or 3.x - up to you) must be under the hood, but you may use any wrapper frameworks.
- Publish your work on your repository at http://github.com and send the link at qa@vinogradov-it.de
- Make sure to include README about how to start you test. Keep in mind, I might have not every library installed, so mention the prerequisites.
- You may use any help from the Internet, just do not let other people write this work for you :)

### Timing
As you have 49 more tests to write (in our fictionaly story), you don't need to make a perfect test. Do just a good enough test for this situation (4 hours for one test on average). Take as much time or as few time, as you need. If you have done your "good enough" test in just one hour - don't make it perfect, you may need the time later for the other tests, that could be more complex. If on the other hand, you think you need more time, e.g. 8 hours - it is fine too, perhaps it will help you to save time in future tests reusing some code or ideas. Let your judgement guide you when to stop. You may write me, how much time it took, but only if you want to.


### Scenario  to automate

User wants to web-search for a "selenide" term getting the popular site as the top hit. Then search for the logo of the site, again hitting the relevant image. After that user returns to the "web search", and the result is still there. 

1. Goto http://google.com/ncr
2. Search for "selenide"
3. We expect to have a link to selenide.org as top-1 result.
4. Switch to Images search
5. We expect to have the first image to be somehow related to selenide.org site
6. Switch back to "All" link
7. We expect that we still have the same link to selenide.org as in step 3
