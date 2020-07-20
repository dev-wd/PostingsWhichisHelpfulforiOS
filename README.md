# iOS개발에 도움이 되는 포스팅 모음
더 좋은 앱을 만들어 가기 위한 스터디를 하는 도중 국내외 꾸준히 보는 글들을 박-제-합니다👩🏻‍💻
__`주니어 개발자의 학습목록`__


## AutoLayout 
### [Self-Sizing Table View Cells](https://baked-corn.tistory.com/124)
- 이동건님 블로그
- Cell의 높이를 동적으로 지정하는 것에 대한 여러 방법과 차이점이 서술되어 있음

## Clean Arthitecture for iOS
### [iOS-Clean-Architecture-MVVM](https://github.com/kudoleh/iOS-Clean-Architecture-MVVM)
- MVVM Templete Repository
- Domain, Data, Presentation Layer에 대한 자세한 그림 및 프로젝트 제공

### [RxSwift+clean architecture - Tiendeo Tech](https://medium.com/tiendeo-tech/ios-rxswift-clean-architecture-d7e9eaa60ba)
- MVVM + RxSwift (including Domain Layer,  Data Layer)
- MVVM을 Presenter Layer ~ Data Layer를 RxSwift를 활용해 쓰는 예제를 잘 구성하였음

## RxSwift
### [Networking with RxSwift](https://www.netguru.com/codestories/networking-with-rxswift)
- Networking 할 때 RxSwift를 적용하는 방법
- ViewModel & ViewController에서만 RxSwift를 적용할 것인가? 
- Networking Layer러 부터 RxSwift를 적용하는 것이 더 좋은가? 에 대한 고민을 할 때! 참고!

### [힐페TV - ViewModel을 무조건 믿을 수 있는 방법이 있다???(삐슝빠슝)](https://blog.gangnamunni.com/post/HealingPaperTV-ViewModel-Test)
- 힐링페이퍼 블로그
- MVVM + RxSwift를 적용한 간단한 앱 구현
- Input, Output을 명확하게 명시하여 구분
- Data 최적화를 Transform 로직을 이용하여 구현
- Test Code 작성, RxNimple 활용
- VieModel뿐 아니라 Network Layer도 'Moya/RxSwift'를 활용항 개발함

### [RxAnimated — animated bindings](https://medium.com/flawless-app-stories/rxanimated-animated-bindings-c5daa7f7d591)
- RxCocoa 를 Extention으로 animation을 주는 방법
- RxAnimated 추가 

### [RxSwift and Animations in iOS](https://www.toptal.com/ios/rxswift-animations-ios)
- UIView.animate를 RxSwift에 넣지 않고 반응형으로 구현하는 방법 제시
- Observable을 Create하고 스트림 단계를 연결하여 붙여줌으로써 반응형으로 구현하는 것이 가능하다.
- 복잡하 Animation들의 통합이 필요할 때에 참고하기가 좋음

## Test Code 
### [UnitTest for Xcode](https://velog.io/@wimes/UnitTest-for-Xcode)
- 한국어 리소스
- Unit Test에 대한 기본적인 설명이 국내 자료는 내용을 많이 생략하고 방법만 적은 것이 많은데, 인과적으로 근거를 두고 잘 설명하고 있음

### [iOS Unit Testing and UI Testing Tutorial](https://www.raywenderlich.com/960290-ios-unit-testing-and-ui-testing-tutorial)
- Raywenderlich의 Unit Test 예제
- given, when, then의 순서를 지킴
- Fake Object 구현 (Mock, Stub)
- 퍼포먼스 테스트 구현
- 네트워크 테스트
- 장점: 프로젝트 단위로 어떻게 테스트 코드를 작성하는지 참고가 가능

### [Testing Your RxSwift Code](https://www.raywenderlich.com/7408-testing-your-rxswift-code)
- 프로젝트에서 RxTest, RxBlocking을 어떻게 적용하는지 학습
- 다양한 환경에서 RxTest, RxBlocking 중 어느것을 사용하는 것이 적합한지 학습
- 프로젝트 Test번들 처음 Add할 때 엉뚱하게 많이 해매는데 이를 말끔하게 해결해준 포스팅

## Managing enterprise-app
### [Enterprise 규모 앱 환경 구성 - 1](http://minsone.github.io/ios/mac/ios-enterprise-app-configuration-1)
### [Enterprise 규모 앱 환경 구성 - 2](http://minsone.github.io/ios/mac/ios-enterprise-app-configuration-2)
- 민소네님 포스팅
- 기업규모 앱의 Layer 나누기
- 라이브러리 의존성 제거, 불필요한 프로토콜 제거, 빌드 타임 감소

### [디버깅 시작해버깅](https://speakerdeck.com/gaeun/dibeoging-sijaghaebeoging)
- 가은님, Let us go 발표자료
- 빌드 타임이 오래 걸리느 프로젝트에서 불필요한 build를 줄이기 위한 디버깅
- LLDB와 친해지기

### [[Xcode][LLDB]Debugging With Xcode and LLDB](http://minsone.github.io/ios/mac/xcode-lldb-debugging-with-xcode-and-lldb)
- 민소네님 포스팅 
- 위 가은님의 발표자료가 기능에 따라 사용법을 발표를 했었다면, 민소네님은 LLDB 명령어를 중심으로 기술함
- 실제 예제를 통해서 서술이 되어 따라해볼 수 있음

### [iOS 서버별 자동배포 환경 구축 방법](https://magicmon.github.io/2019/01/07/iOS-Automated-Deployment-Environment/)
- Xcode + Jenkins 설정을 통해 각 서버별로 자동배포 가능하도록 구축하는 방법
- 코드 수정 없이 각 서버 및 조건 별로 배포가능 하도록 환경설정 하는 방법

## Fastlane
### [Fastlane Docs](https://docs.fastlane.tools/getting-started/ios/setup/)
- Fastlane 공식문서

### [Fastlane. tutorial: Getting Started](https://devmjun.github.io/archive/Fastlane)
- 한국어 리소스
- 각각의 lane들의 역할과 이를 응용하여 활용하는 방법을 구체적으로 적어놓았음
- 이를 단순히 코드 하나로 실행하는 것을 넘어서서 다른 툴과 연동해서 사용하는 방법을 고민해야한다.

### [Implementing fastlane from nothing to App Store, Josh Holtz](https://www.youtube.com/watch?v=6Jz-Ywxki0U)
- 해외 유튜버, 처음하는 사람들이 순서대로 잘 따라할 수 있도록 단계별로 동영상으로 설명해줌
- 2020.04.27 내 생일에 올라온 영상..


## SwiftUI, and Combine
### [SwiftUI+MVVM](https://github.com/kitasuke/SwiftUI-MVVM)
- SwiftUI+Combine으로 MVVM 아키텍쳐 구성
- 일본 분이 만드신 리포지토리, 스타가 350개 넘음
- UI 및 Unit Test 또한 작성되어 있다.

## Network 
### [Swift, Moya가 무엇인지, 어떻게 사용하는지 알아봅니다](https://devmjun.github.io/archive/Moya-Tutorial)
- Moya Library에 대한 이해
-  Alamofire와의 관계
-  사용방법 및 장점

## Memory ManageMent
### [iOS 메모리 뜯어보기, 메모리 이슈 디버깅하기, 메모리 릭 찾기](https://seizze.github.io/2019/12/20/iOS-메모리-뜯어보기,-메모리-이슈-디버깅하기,-메모리-릭-찾기.html)
- 메모리 뜯어보는 몇가지 방법 소개, 채완님 블로그
- 설명이 디테일함, 해당 글의 레퍼런스를 참조해서 메모리 관리 전략을 짤 예정

### [Practical Dependency Inversion in Swift](https://medium.com/flawless-app-stories/practical-dependency-inversion-in-swift-1c1142161a8)
- 두 객체 사이의 강한 의존성 고리를 끊기 위해서 의존성을 역전하는 방식
- 레츠스위프트 뉴스레터 8호 소개 해외글
- 의존성 제거를 매니징하는 것에 대해 스탠다드가 없는데, 한가지 방법으로 공부하면 좋을것 같다는 생각


