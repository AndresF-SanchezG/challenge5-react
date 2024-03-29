# Build a 25 + 5 Clock

Build an app that is functionally similar to this: https://25--5-clock.freecodecamp.rocks.

Fulfill the below user stories and get all of the tests to pass. Use whichever libraries or APIs you need. Give it your own personal style.

# Targets

- User Story #1: I can see an element with id="break-label" that contains a string (e.g. "Break Length").
- User Story #2: I can see an element with id="session-label" that contains a string (e.g. "Session Length").
- User Story #3: I can see two clickable elements with corresponding IDs: id="break-decrement" and id="session-decrement".
- User Story #4: I can see two clickable elements with corresponding IDs: id="break-increment" and id="session-increment".
- User Story #5: I can see an element with a corresponding id="break-length", which by default (on load) displays a value of 5.
- User Story #6: I can see an element with a corresponding id="session-length", which by default displays a value of 25.
- User Story #7: I can see an element with a corresponding id="timer-label", that contains a string indicating a session is initialized (e.g. "Session").
- User Story #8: I can see an element with corresponding id="time-left". NOTE: Paused or running, the value in this field should always be displayed in mm:ss format (i.e. 25:00).
- User Story #9: I can see a clickable element with a corresponding id="start_stop".
- User Story #10: I can see a clickable element with a corresponding id="reset".
- User Story #11: When I click the element with the id of reset, any running timer should be stopped, the value within id="break-length" should return to 5, the value within id="session-      length" should return to 25, and the element with id="time-left" should reset to its default state.
- User Story #12: When I click the element with the id of break-decrement, the value within id="break-length" decrements by a value of 1, and I can see the updated value.
- User Story #13: When I click the element with the id of break-increment, the value within id="break-length" increments by a value of 1, and I can see the updated value.
- User Story #14: When I click the element with the id of session-decrement, the value within id="session-length" decrements by a value of 1, and I can see the updated value.
- User Story #15: When I click the element with the id of session-increment, the value within id="session-length" increments by a value of 1, and I can see the updated value.
- User Story #16: I should not be able to set a session or break length to <= 0.
- User Story #17: I should not be able to set a session or break length to > 60.
- User Story #18: When I first click the element with id="start_stop", the timer should begin running from the value currently displayed in id="session-length", even if the value has been   incremented or decremented from the original value of 25.
- User Story #19: If the timer is running, the element with the id of time-left should display the remaining time in mm:ss format (decrementing by a value of 1 and updating the display       every 1000ms).
- User Story #20: If the timer is running and I click the element with id="start_stop", the countdown should pause.
- User Story #21: If the timer is paused and I click the element with id="start_stop", the countdown should resume running from the point at which it was paused.
- User Story #22: When a session countdown reaches zero (NOTE: timer MUST reach 00:00), and a new countdown begins, the element with the id of timer-label should display a string           indicating   a break has begun.
- User Story #23: When a session countdown reaches zero (NOTE: timer MUST reach 00:00), a new break countdown should begin, counting down from the value currently displayed in the             id="break- length" element.
- User Story #24: When a break countdown reaches zero (NOTE: timer MUST reach 00:00), and a new countdown begins, the element with the id of timer-label should display a string indicating   a  session has begun.

# Solution Challenge
In this challenge I tried to get as close as possible to your solution:
- Live Site URL: [Codepen](https://codepen.io/Andr-s-Fernando-Sanchez-Galarza/pen/YzRzwpe)

# Author

- Author - [@AndresF-SanchezG](https://github.com/AndresF-SanchezG)
- School - [Freecodecamp](https://www.freecodecamp.org/)
- Curse - [Build a 25 + 5 Clock](https://www.freecodecamp.org/learn/front-end-development-libraries/front-end-development-libraries-projects/build-a-25--5-clock)








