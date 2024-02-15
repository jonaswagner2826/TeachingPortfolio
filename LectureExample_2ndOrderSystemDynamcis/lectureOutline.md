# 2nd-Order System Dynamics

The format will be the same as before: 20 minutes for a teaching demonstration, and 20 minutes for questions from the committee. 
Questions may be technical about your lecture, or general about your interest and philosophy of teaching.

Give an introduction to second order systems, including the time response to a step input, and an example of an engineering system that has second order behavior.

A decision and feedback (if pertinent) will be communicated to you via email.

## Questions (although the answer is likely known)
- What textbook is used in System Dynamics Modeling and Analysis?
  - Dr. Li: (System Dynamics 3rd Edition)
  - @jruths: do you have a textbook of choice?
  - **Use the most useful example from book?**
- What does "decision and feedback" refer to... 
  - i.e. what did Justin ask/plan for me when requesting this interview?
  - start w/ 2nd semester me grad fellowship or direct to instruction?
- Audience?
  - Is this a physics 1 type class or a 3000-level systems modeling course? (likely 2nd)?
- What level of math vs intuitive understanding do I focus on?
  - By math I mean that we approach like differential equations and deriving the complementary/natural vs particular/forced responses?
    - Do we know laplace yet? yes... but is it best to start with that?
  - By intuitive I'm thinking experimental/design-centric approach
    - examples approach?
    - a physical experiment?
- **Approach of teaching the response???**
  - Laplace -> transfer function
  - diff-eq and solution

## Ideas/Brainstorming
- Engineering System
  - Have a physical example (i.e. spring-mass-damper or other simple physics-type experiment)
  - Use an online/matlab example?
  - Spring-mass-damper (super simple and basic)
  - RLC circuit (not great for ME)
  - Pendulum? (non-linear...)
- Method
  - Whiteboard (an option...)
    - print-out and such like in MECH 4310 review sessions?
  - Presentation
    - Write on slides? (i.e. Shad class) <--- my preference
    - Use as reference w/ whiteboard or similar *** (I agree mostly w/ Justin on this choice)
- Interaction/Presentation Style
  - Being humble/laid-back/honest isn't going to work in this demo...
    - Well mabye... just not to the same level as you did when a TA
  - How much 4th wall breaking?
    - Only at start and mabye the end
- 



## Topics

**What should be primary focus??? 20 min is not a lot of time...**

- Math background/into 
  - Make assumption that all math used has been discussed already? (or do we treat this like non-calc physics?... no)
    - Yes... have understanding of differential equations and laplace transforms
    - 
- System introduction
  - Equation of motion modeling (assume did most before so just review?)
  - Motivation... specific system example
- Transient System Response
  - Natural response from initial conditions
  - Forced from an input
    - Transfer Functions?

future/if-time?
- 2nd Order System Response
  - Transient statistics
- steady-state response?
- frequency response
  - make note of this? i.e. input is sinusoidal




## Current Outline/Plan
- Initial Setup/introduction (4th-wall break)
  - Specific demo objective: 
    - demonstrate ability to teach a concept: motivation -> math -> apply to example
  - Method:
    - Ideal in class would be real-time shared notes
    - Use Teams to record and either use oneNote/ write on slides
    - Demo today w/ slides and whiteboard for reliability/redundancy
- Motivation
  - Slides w/ Examples of Systems
    - (From different realms...)
    - Specific example of spring-mass-damper of suspension system (car? or something else?)
    - Return to standard $m \ddot{x} + b \dot{x} + k x = u$
  - Setup example on board for reference
- Math on board
  - Have equations on slides for setup
  - Explain the step response
    - e^{t} method is better intro right? (i.e. say we did this before when deriving laplace version? or do it in this one?)
    - laplace version? (yes)
      - derive $X(s) = H(s) U(s)$
      - use $U(s)$ as step-response
      - split into components for laplace table
      - inverse Laplace in terms of $\Delta(s)$ terms
        - (pick easy examples to do all the small details...)
  - **Bring it to the charectoristic polynomial**
    - Get the response in terms of $\Delta(s)$ terms...
      - 2 real vs repeated vs complex roots
      - damped, critically damped, underdamped
- Bring back to motivating example
  - (results laid out on slides)
  - Have $m$, $b$, and $k$ to tune
  - Get an intuitive understanding first before moving on (the future/not current lecture steps)



Next question:
- Do I do it in the spring-mass-damper the whole time or do derivation in genral...
  - My answer is the general... there's a reason it's in that form

