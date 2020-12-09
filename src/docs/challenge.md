# React JS Coding Challenge

Dear Candidate,

You've made a great impression in our first steps and we would like to move forward with you to the next part
of our assessment. Please note that we appreciate the effort you are putting into the case, as we'd tried solving this challenge ourselves in the first place, so wish you a fruitful time same as us.

This little puzzle was created in a way to give you maximum freedom, so you can show us the best of your expertise.
Roughly you will have **one day** to do it in.

## The task

We would like you to implement a simple Android/iOS application to define assesment kits including questions for job candidates. Also job candidates can login to the application and answer to the assesment kits.

The following user stories should be implemented:
1) As an Admin user, I need to login to the application (users list is inside `src/data/users.js`) and define new assesment kits (You can find a sample kit in `/src/data/kit_sample.js` and also question types in `src/data/question_types.js`).
Assesment kits should be stored and persisted and also Admin user can "CRUD" these kits.
2) As an Admin user I need to see list of assesments that are answered by candidates.
2) As a Candidate user I need to see assesment kits defined by admin, select a kit and start answering to kit questions. My Answers should be stored and persisted.
3) As a Candidate user I need to see list of kits that I answered before.

#### The constraints

We kindly ask you to commit to the following points:

- The language of implementation: our teams work ES6+, so we would like you to stick to that;
- We firmly recommend you not to use data sources, such as realm, sqlite. Pls stick with Redux, Redux-persist
- Provide documentation. We expect to find at least following data in your README file:
   * We need to know, how to launch your application
   * We need to know the structure of your Application
- Submission: please send us your code in a compressed format; we kindly ask you not to publish your implementation, to avoid online spoilers;

#### Boilerplate  

- We work with React Native framework, and therefore we've prepared this skeleton based on it.

  Be pragmatic and focus on user stories as our review will be mainly based on their implementation.

#### Our review

The review will focus on answering the following questions:

*Architecture*
  - How cleanly can you separate concerns in your code?
  - Does the code demonstrate a good grasp of design?
  - Will your code be easily extensible?
  - Are SOLID principles violated?
  - How good your models are designed? Do they make sense?

*Clarity*
  - Are your dox clear?
  - Is your code orderly and well-commented? Or is it so human readable that documentation would be redundant?
  - Does your solution contain any dead/redundant code (including parts of this skeleton)?

*Correctness*
  - Does your application get launch?
  - Does the application do what it promises?
  - Can we find bugs or trivial flaws?

*Testing*:
  - Is your code/application fully able to test?
  - Did you provide at least some tests? Are they green? Can you provide metrics about it?

We will also highly appreciate the following:

- Production readiness: did you provide a complete product that can be simply put to production?
The following things most probably will not impress us:
- Over-engineering
- Implementing additional features

And finally let us give you advice, which practices should you avoid in your code:

- "Fat" methods
- Using global variables
- Typos, grammar mistakes in a variable naming

*Good luck and have fun!*
