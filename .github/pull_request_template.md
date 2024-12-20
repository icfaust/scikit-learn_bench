## Description

_Add a comprehensive description of proposed changes_

_List associated issue number(s) if exist(s): #6 (for example)_

_Documentation PR (if needed): #1340 (for example)_

---

PR should start as a draft, then move to ready for review state after CI is passed and all applicable checkboxes are closed.
This approach ensures that reviewers don't spend extra time asking for regular requirements.

You can remove a checkbox as not applicable only if it doesn't relate to this PR in any way.

Checklist to comply with **before moving PR from draft**:

**PR completeness and readability**

- [ ] I have reviewed my changes thoroughly before submitting this pull request.
- [ ] I have commented my code, particularly in hard-to-understand areas.
- [ ] I have updated the documentation to reflect the changes or created a separate PR with update and provided its number in the description, if necessary.
- [ ] Git commit message contains an appropriate signed-off-by string _(see [CONTRIBUTING.md](https://github.com/intel/scikit-learn-intelex/blob/main/CONTRIBUTING.md#pull-requests) for details)_.
- [ ] I have added a respective label(s) to PR if I have a permission for that.
- [ ] I have resolved any merge conflicts that might occur with the base branch.

**Testing**

- [ ] I have run it locally and tested the changes extensively.
- [ ] All CI jobs are green or I have provided justification why they aren't.
- [ ] I have extended testing suite if new functionality was introduced in this PR.
