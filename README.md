# FullCalendar-
1_FullCalendar.jsp

      일반 캘린더 생성
2_FullCalendar_add.html

      날짜 클릭하면 캘린더 추가 가능하게하는 기능 
      날짜 지정 할 때 '2022-11-12' 처럼 문자로 지정함.  
      이렇게하면 달력에 일정을 생성할 때 끝나는 날 전날(-1)까지 색칠해준다.
      2022-11-11 ~ 2022-11-13 >> 11일부터 12일까지 칠해준다.
3_FullCalendar_time

      [2]에서 날짜 지정 타입을 문자('2022-11-12') -> 날짜(new Date(...)) 타입으로 변경.
      달력에 일정을 생성할 때 Date타입으로 지정하면 하루짜리 일정은 점으로 표시되고
      일정 범위도 제대로 잡아준다.
      대신 일정을 생성할 때 title 앞에 몇시 일정인지를 표시해준다. ex) [오전 9시 맥모닝먹으러가기]
