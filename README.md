## Progress
- Part 6 next:
(https://docs.djangoproject.com/en/3.0/intro/tutorial06/)

## Feature Ideas
- We could also improve our application in other ways, adding tests along the way. For example, it’s silly that Questions can be published on the site that have no Choices. So, our views could check for this, and exclude such Questions. Our tests would create a Question without Choices and then test that it’s not published, as well as create a similar Question with Choices, and test that it is published.

- Perhaps logged-in admin users should be allowed to see unpublished Questions, but not ordinary visitors. Again: whatever needs to be added to the software to accomplish this should be accompanied by a test, whether you write the test first and then make the code pass the test, or work out the logic in your code first and then write a test to prove it.


## Getting Started

### Activate Virtual Python Environment
`source djangoplay/bin/activate`

### Run Dev Server
`python manage.py runserver`