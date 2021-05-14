## <center>Part3 Yifan Zuo

- Context and scenario:

  For some university students who have group projects and need to take remote video conferences with group members sometimes. There are several reasons to hold a video conference, group members cannot meet each other for special time such as quarantine; Group members may be at different physical locations; Taking video conferences is time-saving and convenient. They might firstly create an account and also create a group meeting room if there isn't one, then inviting their group members to the virtual meeting room. After this, any team members could hold a conference at any time, and other team members can attend or absent the conference.

- Potential target user:

  Our potential user are university students who have project and want to collaborate each other by long-distance vedio-conference. They might used similar interface before. They could use the application anywhere with internet by their device(mobile phone, tablet, laptop...etc).

- Representative tasks:

  - Join project 1 conference and then check project 1 recording 1, then back to main screen.

  - Table:

    | **Action Sequence**        | **Does the user know what to do given the action?** | **Can the user find the right interface component to perform this action?** | **Can the user associate the feedback from the interface to the correct action they perform?** | **Does the user understand the feedback so that they know where they are in the task after performing the correct action?** | notes                                                        |
    | -------------------------- | --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
    | Login                      | Yes                                                 | Yes                                                          | Yes                                                          | Yes                                                          |                                                              |
    | Select project 1           | No                                                  | Yes                                                          | No                                                           | No                                                           | Problem: User can't select project they want to join, Suggestion: we could add option when click the join button |
    | Join project 1             | Yes                                                 | Yes                                                          | Yes                                                          | Yes                                                          | Problem: meaning of share screen button and switch button in meeting screen not clear, Suggestion: remove switch button and change share screen description from "share" to "share screen" |
    | Back to main screen        | Yes                                                 | Yes                                                          | Yes                                                          | Yes                                                          |                                                              |
    | Go to recording            | Yes                                                 | Yes                                                          | Yes                                                          | Yes                                                          |                                                              |
    | select project 1 recording | Yes                                                 | Yes                                                          | Yes                                                          | Yes                                                          |                                                              |
    | Play the recording         | Yes                                                 | Yes                                                          | Yes                                                          | Yes                                                          |                                                              |
    | Back to main screen        | No                                                  | No                                                           | Yes                                                          | Yes                                                          | Problem: the first user back to main screen from meeting screen ,user know to click "liitle house" button, the second time user back to main screen from recording screen, user confused with with the "liitle house" button he previously click and the main screen blue button. Two buttons not consistent. Suggestion: remove the "liitle house" functionality, and add a main screen button in meeting screen. |

    Other problem: Sidebar functionality doesn't clear, user doesn't know what the liitle square button means. 

    Suggestion: change the liitle square button to arrow button, also change the position at the middle of the box.