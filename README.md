# dirary-backend
일기장 기능을 제공하는 Backend System(Spring-boot)

## 기능

1. 일기 쓸 거리 제공
1. 이미지 & 테그 삽입 기능 
1. 마크다운 문서 작성 기능
1. Federation log-in
1. SNS 연동 기능
1. 날씨 연동 기능
  - When user write a diary this component call a weather API and save it along with the diary
  - They can read it with a weather icon.
  - The weather API contains temp, rain, wind, humi.. so on.
1. 검색 기능을 통한 다른 사용자의 일기 열람 기능(공개/비공개 설정 가능)
1. 등록된 사용자의 Follow / Unfollow 기능
1. 타임라인을 통해 자신이 Follow 하고 있는 사용자들의 일기가 보여지는 기능
1. Push an alarm to smart phone if there is anything to notify.
1. automatic completion function(typing)
1. share events, schedule function
1. simple adding fuctino(ex: @12 6 930 17 metting LC A) -> (add scedule 6th of DEC. 9:30 ~ 17:00 "meeting LC" with Alarm)
