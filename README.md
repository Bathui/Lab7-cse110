## Team member
1. Hui Cui (myself)

## Questions
1. **Option 1**. This is because the automated test is integrated into our CI pipeline, so running with github action could make sure that bugs can be caught in the early stage and make sure individual with broken code pollute the main branch. Also, it makes each member in the team consistent with the feedback from the testing. And it also helps to improve scalability in our project. Option 2 cannot make sure each member as the same testing, and option 3 cannot catch the bugs in early stages and fix them.

2. No. E2E is for checking the entire flow of our application. So, it is not for checking the correctness a specific detail like individual functions. If we want to check individual functions, unit tests will be a better choice, like we did in the last lab. 

3. Difference: Navigation mode analyzes the page after it loads, and evaluates overall performance. However, it does not handle uer interactions or changes in the pages after the page loading. Snapshot mode analyzes the current state, and handls accessibility issues, but it cannot evaluate the performance of JS or changes in DOM tree, which is pretty different from navigation mode.

4. First, we need to improve the accessibility, since it is 90 currently. So we still need to tweak the contrast ratio between text and background. Also, add more proper aria-labels could be a good choice to improve the score. The second thing is to improve SEO, which is 91 right now. Having more organized hierarchy could be helpful and also adding meta discription and alt for images also helps. The last thing to improve is best practices, which is 96, although it is pretty good now. We can use all images over HTTPS and use modern formats and also to avoid inline JS to improve the score. Console errors or warnings could also be the issues.



