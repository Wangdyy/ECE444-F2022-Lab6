# ECE444-F2022-Lab6

### Pros and Cons of TDD
Pros of TDD is that test cases are easier to maintain and modularize. Each test is specific for one feature and the interfaces do not overlap with each other and it is easier to take care of. When needing to rewrite a feature, you do not need to rewrite the test since the test case would only be testing that specific feature. As long as every specific test case passes, it is fine. There is also less debugging since each test case would only be testing one individual feature. So, if there is something wrong with the code, it is easy to point out since you would pinpoint it to which test case failed which would indicate where exactly the bug is. 

Cons of TDD is that it takes a longer time, since test cases needs to be written for every single test cases. Simple implementations would still need tests to be written for them which results in writing and testing these test cases before writing the code itself. Also, as the requirements change or the code changes, the test cases would have to change too to satisfy the new requirements. With TDD, you would have to change the tests and test them first before you write the code, which takes a long time to do for new modifications every time a requirement is changed. 

### Test Cases I added to Project:
test_search_endpoint()  
test_database()  
test_course_details_endpoint()

Lines: 5-20

https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-11-swat/blob/main/Education_Pathways/tests/test_app.py#L5-L20
