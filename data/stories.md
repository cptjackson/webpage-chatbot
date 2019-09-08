## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path
* greet
  - utter_greet
* mood_unhappy
  - utter_sad

## say goodbye
* goodbye
  - utter_goodbye

## music
* music
  - utter_music

## Songs
* songs
  - utter_songs

## Songs - deny
* songs
  - utter_songs
* deny
  - utter_sad

## After You
* explain_song{"song":"After You"}
  - utter_after_you

## Obvious
* explain_song{"song":"Obvious"}
  - utter_obvious

## Stand Still
* explain_song{"song":"Stand Still"}
  - utter_stand_still

## technology
* technology
  - utter_technology

## experience
* experience
  - utter_experience

## work
* work{"work_type":"rbc"}
  - experience_form
  - form{"name":"experience_form"}
  - form{"name":null}
