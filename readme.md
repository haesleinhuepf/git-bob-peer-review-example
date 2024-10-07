# git-bob peer review example

In this repository, we demonstrate how to use [git-bob](https://github.com/haesleinhuepf/git-bob) for peer review.
There are four git-bobs configured in this repository who will respond to pull-requests in an organized way. 
There is an editor who will manage the interaction with three reviewers who will review your pull-request.
The three reviewers are configured differently. 
* Reviewer1 is overly positive, basically accepting all modifications. 
* Reviewer2 is a bit rude and very negative. They will reject all modifications.
* Reviewer3 will provide constructive feedback and if the modification is not good enought, it will suggest improvements.
* The editor will summarize the feedback and provide a final decision.

This demonstration is for academic purposes. If you plan to use artificial intelligence based tools such as git-bob for reviewing pull-requests, it might make sense to not re-use reviewers 1 and 2 and put more effort into designing the prompt of reviewer 3.

