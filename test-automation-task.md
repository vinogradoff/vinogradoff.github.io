###Task
Please automate the following actions as **one** UI Selenium-based test.
Imagine, it is end-to-end test to make sure user could use web and image search as in screnario below.

###Rules

- Use your favorite programming language (e.g. Java, JavaScript, Python, Ruby, C# or whatever you know best).
- You may use any helping framework if you want to.
- Imagine you had at most 4 hours to write this ui-test. Do what you think would be a "good enough" test on your project
  - take as much time as you *need* for your "good enough" test. If it is ready after just 1 hour, it is fine - don't make it perfect! If you needed 8 hours (because you googled or solved problems - it is okay too!)
  - you can write how much time it took, but only if you want to.
- Design it as **one** test, not three, not five. You may have more than one asserts your test.
- Publish your work on your repository at http://github.com and send the link at qa@vinogradov-it.de
- Make sure to include README about how to start you test. Keep in mind, I might have not every library installed, so menthion the prerequisites.
- You may use any help from the Internet, just do not let other people write this work for you :)


###Actions to automate

1. Goto http://google.com/ncr
2. Search for "selenide"
3. We expect to have a link to selenide.org as top-1 result.
4. Switch to Images search
5. We expect to have the first image to be somehow related to selenide.org site
6. Switch back to "All" link
7. We expect that we still have the same link to selenide.org as in step 3
