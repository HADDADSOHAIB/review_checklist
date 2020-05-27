# review_checklist

### Step 1 - Prepare

- [ ] Make sure that my work enivroment is quiet and inform my family that I will start working.
- [ ] Remind yourself how important is your work [[more]]
- [ ] Claim pending *Code Review Request (CRR)* [[more]]

### Step 2 - check if code review request is valid

- [ ] Verify if repo looks professional - as requested [here](https://microverse.pathwright.com/library/fast-track-curriculum/69047/path/step/66243642/)
    - Make sure that students added descriptive README file, meaningful commits messages and a title and a short summary for their Pull Requests.
    - Ask student to make their repo professional and to resubmit for review. Example:
         > Friendly reminder: You should make sure that your repo looks professional before review.
         > Please take a step back and read a lesson here https://microverse.pathwright.com/library/fast-track-curriculum/69047/path/step/66243642/.
         > Then apply 3 simple rules from this lesson (it will be easy as you can use a template provided there).
         > This Code Review Request will be marked as invalid in your Dashboard, so please submit a new one once you are ready!
    - **report Code Review Request as invalid if these conditions are not met**
- [ ] Verify correct use of the Github Flow or Git Flow [[more]](./03_flows.md) as requested [here](https://microverse.pathwright.com/library/fast-track-curriculum/69047/path/step/66250306/) and [here](https://microverse.pathwright.com/library/fast-track-curriculum/69047/path/step/59882084/)
    - Ask student to use Github/Git Flow in the CURRENT project. Example:
         > Friendly reminder: You should use Github/Git Flow in this project.
         > Please take a step back and watch video here [LINK to Pathwright lesson].
         > Then create a brand new repo with correct setup and feature branch (with DESCRIPTIVE name) and copy your code there or close this pull request and create another one with correct feature branch .
         > This Code Review Request will be marked as invalid in your Dashboard, so please submit a new one once you are ready!
    - **report Code Review Request as invalid if these conditions are not met**

### Step 3 - review Pull Request

- [ ] Check linter errors as requested [here](https://microverse.pathwright.com/library/fast-track-curriculum/69047/path/step/54883773/) and that students uses config files copied from [config linters repo](https://github.com/microverseinc/linters-config#linters-config)
    - **report Code Review Request as invalid if these conditions are not met and this was required by the project**
- [ ] Open ["Code review guidelines"](https://gitlab.com/microverse/guides/tse/code_review/code_review_guidelines) based on project requirements and check the requirements for the project you are reviewing.
    - [ ] **Always remember to explain WHY you request a change and add a screenshot of it .**
    - [ ] Run the pre-built tests (when available)
    - [ ] Go through the "Minimum Requirements Checklist" (**don't approve the project if one of this is not met**)
        - Copy checkboxes with the requirements that are not met.
        - Leave comments directly under the line of code that you want the student to modify.
    - [ ] Go through the "Stretch Requirements Checklist"
        - Add `[OPTIONAL]` at the beginning of your comment and mention that it is not required to mark the project as approved.
    - [ ] [OPTIONAL] Add your own comments
        - Add `[OPTIONAL]` at the beginning of your comment and mention that it is nor required to mark the project as approved.

### Step 4 - complete code review request

- [ ] Summarize the result of your code review
    - `Approve` **OR** `Request changes` in the Pull Request.
    - Remember about giving a kind summary in the final comment.
    - **Find positive words to share in your summary, particularly when you have requested for changes multiple times. This is when they are needed the most.**.
- [ ] [OPTIONAL] Remember about emojis and gifs. They will make your code review more human-friendly 👽👽👽.
- [ ] Mark review as completed in the [dashboard](https://dashboard.microverse.org/code_review_request)
