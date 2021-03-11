# Foundation Baseline

### For your information

- Ngrx, bootstrap and angular cli are already installed
- There is no terminal or git here, so to create a component or similar right click on the folder you want to
  create one in.
  angular generator > component
- Font sizes do not need to be same, pixel perfect not required. use h tags
  and bootstrap grid to align things

- Icons are from font awsome

  - user
  - bell
  - circle check
  - times circle

- This is testing component naming, placement and use as well as state managment, google chops and using your
  resources. (For this situation Sr Devs are not a resource, this is not realistic for everyday work.)

- There are colors provided for success, error, and info as well as a adequate dark and light gray. With some
  text-color classes added. Check styles.scss chances are what you need is there.
- I will be doing this exercise too, it is only fair.
- We will talk through what we did breifly and use this information for when we refactor components. Starting
  March 16th

#### What you're supposed to do

- Recreate the interaction using

  - [mockup 1 user](https://github.com/kaseymccormick/angular-exercises/blob/main/foundation-baseline/admin-view.svg)
  - [mockup 2 admin](https://github.com/kaseymccormick/angular-exercises/blob/main/foundation-baseline/user-view.svg)

- clicking user must show user view and change headline
- clicking admin must show admin view and change headline
- do this in responsible amount of components, code should be minimaly copied.
  Meaning there shouldn't just be three components for this.

- state manage the click count of checkmark(increase) and x(decrease) on a favorite color, emulating a voting
  system
  here.

  - # is a placeholder for the state managed voted number

- use bootstraps card system with header and footer, as well as bootstrap buttons.
- share button should be disabled
- when you click add button have an bootstrap danger alert show up saying Sorry, not available <b>yet</b>
- time yourself, use toggle, stopwatch paper and pen I don't care. try and get within 15 minutes of reality.

      - I'm not 'grading' on timing, knowing where the struggle is helps.
      - you knowing how long a task takes you helps
      - I'd break up timing into <ol>

  - planning
  - component creation/ file setup
  - state management
  - cleanup : checking files for console.logs, comented out code, making coments for fellow team members,
  adding link to your stackblitz to your ticket & updating ticket
  </ol>

- Ready to get started? Fork this repo, hit save once you're logged in then, [good luck.](https://media.giphy.com/media/kVaj8JXJcDsqs/giphy.gif)
