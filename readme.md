<p align="center">
  <img src="https://github.com/cheezbit/classroom-call/blob/master/res/gopher.png" height="120px" />
</p>

---

## Idea

Having now been through a semester of online school, I can say with confidence that it **sucks**. Teachers struggle to keep a classroom of students engaged. Class discussions are chaotic in Zoom. Teachers can't tell if students are struggling because they see only small icons on a screen. 

Students too are struggling in this new system. Many students fade  into the background, their questions go un-asked or un-answered.  Others log in to Zoom then put Netflix or another program on in another window.

**Gopher EDU** aims to address the problems posed by remote learning by bringing new engagement tools to the classroom. We want to replace the chat feature with a class question feature so students can ask questions in a more streamlined way. We envision a live quiz feature to help teachers keep their classes engaged and better assess learning. We aim on offering many other features, all with the goal of making online learning more engaging for everyone involved.





## Feature Spec

| Feature                   | Description                                                                                                                                                                                                                                                                                  | State |
|---------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| Question Live Feed        | Zoom chat is disorganized. We envision an easy way for students to ask questions, that works in the same vane as Instagram or Facebook live. Teachers can choose to show or hide questions, or pin questions for discussion. Students can like questions if they want them to be addressed.  | In progress     |
| Teacher Live Assessment   | The teacher can give a live multiple choice question, to keep students engaged, and to gage class understanding. They should be able to set time limits in a jeopardy or Kahoot fashion.                                                                                                     | In progress     |
| Group students            | Break class into discussion groups button                                                                                                                                                                                                                                                    | ❌     |
|  Presentation modes | Teacher should be able to give students the ability to get center focus for questions. By default the teacher should have presentation mode                                                                                                                                                                                                       |  Teacher presentation mode is done -- student presentation mode is in progress     |
| Full asessments           | Teachers should be able to run assessments through the platform during, before, or after a call.                                                                                                                                                                                             | ❌      |
## Tech Stack 

### Backend
<img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/kub.png" height="80px" /> <img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/dock.png" height="80px" /> <img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/go.png" height="80px" />  <img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/red.png" height="80px" /> <img src="https://github.com/cheezbit/classroom-call/blob/8f04e122ef5cdbd52515446991631f90652f7dde/readmeImages/gcloud.png" height="80px" />

### Frontend
<img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/react.png" height="80px" /> <img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/redux.png" height="80px" /> <img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/sass.png" height="80px" />  <img src="https://github.com/cheezbit/classroom-call/blob/19d08ec509588bd8fdfea8b6b75a15964fb9a181/readmeImages/web.png" height="80px" /> <img src="https://github.com/cheezbit/classroom-call/blob/e75537c05a17b7e1b2d1ff15207dd4d81ae7259a/readmeImages/type.png" height="80px" />

### Technical Challenges
- [x] SSL Termination
- [x] P2P Connections (STUN Archeticture)
- [x] Data channels
- [x] Kubernetes Setup + Autoscaling
- [x] External Load Balancer Configuration
- [x] WebRTC + Redux configuration

### Branding
<img src="https://github.com/cheezbit/classroom-call/artboard.png"/>

### Open Source Creds
We based our project on the [Peer Calls](https://github.com/peer-calls/peer-calls) Project

