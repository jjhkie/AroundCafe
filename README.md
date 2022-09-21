# AroundCafe
Kakao API를 사용한 주변 카페 찾기

## [ 사용한 기술 ]

  - Snapkit  
  - RxSwift  
  - RxCocoa



## [ Point ]

	1. KAKAO API 사용
		- kakao developers 에서 내 애플리케이션 등록 후 bundle ID 등록
		-  info - Information Property List - KAKAO_APP_KEY 에 네이티브 key 등록
		-  https://apis.map.kakao.com/ios/guide/ 에서 sdk 다운 
		- 다운받은 SDK 폴더의 lib 안에 있는 폴더를 프로젝트에 추가해준다.
		- Bridge Header 파일 추가 [ new file - Header File ]  - 해당 파일에 #import <DaumMap/MTMapView.h>  추가
		- 문서에서 요구하는 패키지 추가
		-  [Project] -[ Basic ]- [arc 검색] — [Objective-C Automatic Reference Counting] 의 value = no 로 변경
		- [TARGETS] -[ All ]- [Swift Compiler - General ] - [Objective-C Bridging Header ] 에 전에 만들었던 header File 의 Full Path 의 값을 넣는다.



## [ Add ]
