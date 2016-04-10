# GoogEvent's Idea
===

---

# #The Google Form with User Interface

---

## <a name="main-feature"></a> Main Feature 
### <a name="life-circle"></a> Life Circle

1. Use GoogEvent to create the event
2. Share the created event to WeChat / WhatsApp / Facebook... or anywhere
3. Receiver could open the event by our app and make their response
4. Receiver who made the response will become the participant
4. Creator and participants will be noticed when the status of the created event changed
5. Creator finalize the event
6. All participants will receive the confimed event

### <a name="key-concept-explanation"></a> Key Concept Explanation
#### Event
- The nature of the event is a public accessable URL
- The content of the URL may just be a Json file contains all the necessary information

#### Share （＊Very Important＊)
- We don't need to build our own user system and even don't need to login
- We just take advantages of the existin network (Friends / Group Chat / Public Page)
- The user could select the way of distributing the event and the number of potential receivers (Send to each person one by one / Send to a group chat channel / Publish to the website)
- It may be kind of dangerous that every one known the link could access the event but it also save lots of effort to build a new user network within our App (Take a loot at ZiYue, the app was abandonded by the user since it is so inconvenient to add all the friends again)
- Some simple access-limitation could be provided to the creator such as "Visit Time Limitation"

#### Open the Event
- GoogEvent could interpret the Json file and display some user-friendly interface
- We may could support viewing the URL and making response through the brower later

#### Response
- The content of the URL could be changed after the user making response
- The user could withdraw the response before the event is finalized

#### Notification
- TODO: How to observe the new response / How to notify the Creator and Participants

#### Confirmed Event
- After the user finalize the event, the content of the URL may changed to a new format
- All the responsers could review the finalized event and Quit the event
- Support to add the event to calendar

