# Technical test

## Background:

< describe the background of the challenge >

## The challenge:

< add the challenge specification here > 

You can spend as much time as you wish to come up with a solution that you’re proud of. To pass the test, you don’t need to care about <describe unwanted technical "red herings">

Think of this as an open source project in that sense that if you stumbled across it on a community such as GitHub, what would you want it to look like? The only requirement is that the solution is written in < your programminng language preference if there is any >. Frameworks, or lack thereof, is entirely up to you.

_Hint: We’re looking for a high-quality submission with great application architecture, not a “just get it done”-like approach. Stay away from frameworks/boilerplates that handle everything for you, or use them only as a thin layer, so we can see how you structure applications yourself._

## Extra mile bonus points

- Application logging
- Containerisation
- Authentication
- API client documentation (for example swagger)
- Build script / CI
- Data storage
- Anything else you feel may benefit your solution from a technical perspective.

## What we will be assessing


| Area | Max score |
|----|----:|
| Functionality (does it work?) | 5 points|
| Code Quality |5 points|
| Solution Design |5 points|
| Problem Solving |5 points|
| Automated Tests |5 points|
|**Overall Score**|**25 points**|


Scoring algorithm:

```python

def have_you_passed_the_test(overall_score, bonus_points):
    if overall_score >= 19:
        return True
    elif overall_score > 16:
        return overall_score + bonus_points >= 19

    return False
```

## Improvements

Given more time, what improvements, if any, would you make to your code? Please include this in your repository.

## Submitting

When you’re ready to submit, upload the repository to Github and share it with us!
