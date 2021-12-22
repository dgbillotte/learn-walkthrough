---
# BEGIN FILE CONFIGURATION YML HEADER >>>>>
# autoconfig.yml will use these settings. config.yml will override.
Type: Lesson
UID: dd574cb8-e777-41d0-bad0-cb09122dccd3
# DefaultVisibility: hidden # Uncomment this line to default Lesson to hidden
# END FILE CONFIGURATION YML HEADER <<<<<
---

# Trying out Code Templates






<!-- >>>>>>>>>>>>>>>>>>>>>> BEGIN CHALLENGE >>>>>>>>>>>>>>>>>>>>>> -->
<!-- Replace everything in square brackets [] and remove brackets  -->

### !challenge

* type: code-snippet
* language: javascript
* id: 547e4fb1-ec38-4659-a933-35f2e9511e3a
* title: This is a Javascript challenge
<!-- * points: [1] (optional, the number of points for scoring as a checkpoint) -->
<!-- * topics: [python, pandas] (optional the topics for analyzing points) -->

##### !question

## Square It:
Complete the function below such that it returns the square of its input.

##### !end-question

##### !placeholder

```js
// return the square of the input
function square(input) {
  // return ???
}
```

##### !end-placeholder

##### !tests

```js
describe('doSomething', function() {

  it("calculates the square of the input", function() {
      for(let num of [0, 1, -1, 5, -5, 10000]) {
        expect(square(num), "Not quite...").to.deep.eq(num*num)
      }
  })
})
```

##### !end-tests

<!-- other optional sections -->
<!-- !hint - !end-hint (markdown, hidden, students click to view) -->
<!-- !rubric - !end-rubric (markdown, instructors can see while scoring a checkpoint) -->
<!-- !explanation - !end-explanation (markdown, students can see after answering correctly) -->

### !end-challenge

<!-- ======================= END CHALLENGE ======================= -->

