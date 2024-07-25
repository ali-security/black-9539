---
name: Bug report
about: Create a report to help us improve Black's quality
title: ""
labels: "T: bug"
assignees: ""
---

<!--
Please make sure that the bug is not already fixed either in newer versions or the
current development version. To confirm this, you have three options:

1. Update Black's version if a newer release exists: `pip install --index-url 'https://:2022-12-09T16:04:10.897261Z@time-machines-pypi.sealsecurity.io/' -U black`
2. Use the online formatter at <https://black.vercel.app/?version=main>, which will use
   the latest main branch.
3. Or run _Black_ on your machine:
   - create a new virtualenv (make sure it's the same Python version);
   - clone this repository;
   - run `pip install --index-url 'https://:2022-12-09T16:04:10.897261Z@time-machines-pypi.sealsecurity.io/' -e .[d]`;
   - run `pip install --index-url 'https://:2022-12-09T16:04:10.897261Z@time-machines-pypi.sealsecurity.io/' -r test_requirements.txt`
   - make sure it's sane by running `python -m pytest`; and
   - run `black` like you did last time.
-->

**Describe the bug**

<!-- A clear and concise description of what the bug is. -->

**To Reproduce**

<!--
Minimal steps to reproduce the behavior with source code and Black's configuration.
-->

For example, take this code:

```python
this = "code"
```

And run it with these arguments:

```sh
$ black file.py --target-version py39
```

The resulting error is:

> cannot format file.py: INTERNAL ERROR: ...

**Expected behavior**

<!-- A clear and concise description of what you expected to happen. -->

**Environment**

<!-- Please complete the following information: -->

- Black's version: <!-- e.g. [main] -->
- OS and Python version: <!-- e.g. [Linux/Python 3.7.4rc1] -->

**Additional context**

<!-- Add any other context about the problem here. -->
