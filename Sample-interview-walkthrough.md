## Sample interview walkthrough



#### "real" phone screen:

- asked me about something on my resume that i'm particularly passionate and proud of, why it makes me a good fit for __insert company name__ PM
- *asked me what's a product at _____ I like*
- pivot to product question: *if I was a PM on the ______ team, and wanted to make a new feature, what would be an idea?*
- *how does this feature relate to __insert company name__'s mission?*
- *how would I measure the success of this feature?*
- *say it fails. go back to the drawing board--what's a cool idea for another _feature_?*
- *asked me about a challenging time for leadership??*



#### **"real" first round interview**

```fdlfk
you are given two lists of numbers. their contents are identical, but one list has an extra element. which list has the extra element, and what is it?
```

- not sorted

- may be duplicates

- pos/neg

  

-> input is two lists, output is 1 element

- brute force -- 2x for loop
  
  - O(n^2)
- sort then check
  
  - O(nlogn)
- add all numbers together -> find difference -> return
  
  - O(n)
  
    

```-
design a microwave for the blind.
```

##### customer

- mixed-impaired/nonimpaired family

- primary functionality
  - heating up food, leftovers
  - safety
- cost
  - don't worry about it

##### features:

- voice controlled (*second priority*)
  - set time
  - start/stop
  - open/close door
- change structure from square with door on left side, instead change towards drawer-like structure (*third priority*)
- also add buttons with both text and Braille (*first priority* -- MVP, easiest & critical to implement)
  - for non-impaired members / people who read Braille
- use computer vision / AI to determine contents (*last priority*)

##### use cases: (walk through entire scenario)

- blind family member needs to reheat some leftovers

  1. user approaches microwave with food in hand
  2. user would say "microwave, open door"
     1. microwave echo back confirmation
     2. sensor to guide user into microwave
        1. use computer vision, AI to recommend length of heating ? prioritize
  3. user says "microwave, close door"
     1. microwave echo back confirmation
  4. user sets timer to start
  5. microwave echoes completion

- non-blind adult family member wants to boil water

- blind family member who reads Braille 

- small child tries to accidentally microwave something with alumnium foil / something dumb


##### result--poke holes

- what happens with no internet connection?
- what are other design methods?
- what safety fetures did we not think about?
- how do we get feedback on design?
- what are our highest priority features to enable this?
- how could we reduce cost for a future model?



##### Behavioral

- Why do you want to work in ____?
- What is your favourite product and how will you improve it?
- Name a time there was a conflict during a group project and how did you resolve it?
- Explain the PM position to someone that doesn't get it.







#### **another first round interview**

Phone Interviews:

1. Product Sense - Talked about an app that I like and design decisions I thought made the app special. Also was asked about one of my side projects and explained a design decision I made. I would stress in this interview that you are empathetic about user needs. That seems to be what they are looking for

2. Execution - Was asked a bunch of hypothetical questions "How would you double group joins in 3mo if we gave you a team of 5 engineers." Stress here that you are data driven, use cohort analysis and break users up to prioritize different strategies.
   1. prioritizaiton
   2. time management
   3. tradeoffs
      - "not a right answer"; "as you're making your decisions, think out loud about stakeholders affected by these decisions"
        - both internal and external stakeholders

- future, reasoning, and product
  - tie everything back to __insert company name__ and core products