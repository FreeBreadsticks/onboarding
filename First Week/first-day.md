# Day One of Training

Before the TC begins taking screen shares you will to bring them into a zoom session. Introduce yourself and talk to the TC to get a feel of who they are and where they're at. Make sure they feel comfortable and confident. At this point the new TC should have already shadowed a couple of people on shift a few days prior to their first shift so they should have the gist of the procedure. 

## Shadow Sessions

In this initial meeting explain to them that they will shadow an experienced TC three times. Watch expert chat and slack. Help facilitate these sessions by selecting questions that you feel would be beneficial to their learning. You could also notify the experienced TC they will be shadowed by the new one. Check in with the TC between the screen shares to see if they have any questions about the procedures. Make sure to go over the details of the process and positions:
- Dispatch: This TC works in chat and parses the questions. They will be the one who queues students for screen share.
- Sync: TCs who are in sync wait for the dispatcher to queue the question and then for qbot to assign them to a screen share. They send zoom links to students to pair with them.
- Qbot: Our pal in Slack that lets us know what students are queued, which TCs are assigned and which are free. It's qbot that allows us to organize the screenshares. 
    - Also explain qbot commands and the flow of being assigned a question, `more help`ing a student, and `done`ing a question.


## Mock Pairing Sessions    

Once the new TC has completed the three observations you will want to bring them into another zoom session. Explain that you will now be conducting a mock pairing session in which you will be the student and the new TC will act as the TC supporting the issue.

Before you begin reiterate to them how we expect a TC to handle a screen share with a student. Make sure they understand they should keep their time within 20 minutes, that they should treat the student with respect and empathy, and the importance of using the socratic method to guide the student to the answer. Have 3 labs broken in preparation for these mock pairing sessions. 

Here are 3 that have been used in the past:
- [Tic Tac Toe Status](https://learn.co/tracks/full-stack-web-development-v5/intro-to-ruby-development/ruby-tic-tac-toe/tic-tac-toe-game-status)
- [Sinatra ActiveRecord CRUD](https://learn.co/tracks/full-stack-web-development-v5/sinatra/activerecord/sinatra-activerecord-crud)
- [Filter and Map Lab](https://learn.co/tracks/full-stack-web-development-v5/javascript/looping-and-iteration/filter-and-map-lab)


//TODO: Maybe start a repository with a collection of broken labs? 

How you facilitate the mock sessions is up to you. You may ask a question using AAQ and have the new TC take you from there (as long as AAQ isn't too busy and the dispatcher is aware!). You can also begin the mock session via direct messaging in Slack. Just make sure you try to make it feel as if they are entering a true pairing session. Send a message saying you have an issue with a lab and allow the new TC to send you a zoom link to join them. Remember that the TC should be leading you to the solution via the socratic method. After each session give them feedback. Here's a rubric to help with your feedback:

#### Rating on Scale of 1-5

1. Positive problem solving attitude: 
2. How you engage student in solving the problem: 
3. An encouraging and patient demeanor: 
4. Your ability to use questions to direct student attention and help student think about the problem: 
5. Your ability to gracefully direct student towards google/documentation if it seems like they need it: 

An important aspect of this process is to help build confidence in the TC and make them more comfortable with what to expect. If the TC seems uncertain or less confident be sure to address that by reminding them that the entire team is here to support them and help them in their journey. 


Give details about qbot. About the specific qbot commands, such as qbot in sync, qbot in dispatch (which of course they won’t start out as), qbot out at the end of the day, qbot done for finishing a screen share, and qbot unresponsive as well the guidelines for when to use it, and when to qbot done the unresponsive question.

Qbot commands to go over:
```
qbot in sync - logs in TC as sync support
qbot in dispatch - logs in TC as dispatch support
qbot out - signs out TC
qbot queue <link> - adds question to Q (dispatch only)
qbot take <link> - assigns question to the TC using this command.
qbot unresponsive - If student hasn't responded within 5 minutes, type this in chat to place them back in queue for sleep and send them a message like 'Let us know when you get back!', it was give it to the next TC after 5 minutes. If there is no response, this will be done again and repeated until the student responds or it's been 30 minutes, to where you will qbot done the question.
qbot q - shows a list of all the students in q
qbot who is on? - shows a list of tc's, if they are paired, and how long they've been paired.
```

2. Start out with three roleplay screen shares where you are the student and they are TC (give feedback).

3. Start out with three screen shares letting them shadow you and see your process.

4. Go over any details of the process you take after each screen share to make sure they understand the process.

5. Have the shadower do 3 screen shares while you observe, giving hints in slack if you feel they are lost. If they are unable to figure it out feel free to jump in and help (but only as a last resort). Give feedback after each screen share.

6. After the third screen share you observe. Have them do one on their own without you in the screen share. Let them know if they need help, to tell the student “Let me get another technical coach to assist us with this issue” and give you the link to their screen share so you can join.

7. Once they complete their first screen share on their own successfully. See how they feel about the process and if they are ready to go on their own. Also let them know as colleagues, we’ll be there to help support and to feel free to reach out to us if they get stuck.

8. If they don’t feel like they are ready just yet, let them do one more on their own without you being in the screen share, but acting as a backup. With the same guidelines (see 7 for details).

9. Let them know they are ready to start screen shares and wish them the best of luck and remind them they have the other technical coaches as support.

10. At the end of the day, make sure they qbot out and fill out the end of the day survey(might pair with them in zoom to oversee it)!