Spring 심화 주차 개인 과제 프로젝트

해당 프로젝트는 스파르타클럽의 내일배움캠프에서 진행하는 과제용 프로젝트입니다.

버전에 따라 브랜치를 나누었으며 내용은 아래와 같습니다

Master
: 최종 합본
의도적으로 에러 혹은 비효율적으로 작성된 spring-advanced 프로젝트를 리펙토링한 결과본

LV1
: ArgumentResolver 로직을 정상 동작하도록 수정

LV2
: 1. AuthService의 signup()메서드의 최적화 수행
2. getTodayWeather()메서드의 가독성 향상 작업 수행
3. UserService 클래스의 changePassword() 메서드에서 수행하고 있는 검증을 dto에서 처리하도록 처리

LV3
: n + 1문제를 @EntityGraph로 해결하도록 수정

LV4
: 테스트 코드가 정상 작동하도록 수정
1. PasswordEncdoerTest 클래스의 matches_메서드가_정상적으로_동작한다() 테스트가 정상 작동할 수 있도록 수정
2-1. ManagerServiceTest 클래스의 manager_목록_조회_시_Todo가_없다면_NPE_에러를_던진다() 테스트가 정상 작동할 수 있도록 수정
2-2. CommentServiceTest 클래스의 comment_등록_중_할일을_찾지_못해_에러가_발생한다() 테스트가 정상 작동할 수 있도록 수정
2-3. ManagerServiceTest 클래스의 todo의_user가_null인_경우_예외가_발생한다() 테스트가 정상 작동할 수 있도록 수정


트러블 슈팅 및 해당 과제를 수행하며 공부한 것들을 작성한 TIL블로그 링크
- 
