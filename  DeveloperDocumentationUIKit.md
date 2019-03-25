#  Developer/Documentation/UIKit

> iOS Application 기본 중에 기본. UIKit 스터디를 시작합니다.
>
> - 언젠가 한번 뜯어보고 싶었습니다.



## Contents

- [Overview]()
- [Curriculum]()
- [ContactMe]()

## Overview

##### UIKit은 iOS 또는 tvOS 앱을 위한 그래픽, 이벤트 중심 사용자 인터페이스 구조 및 관리를 담당하는 framework 다.

UIKit framework는 iOS 또는 tvOS 앱에 필요한 인프라를 제공합니다. 인터페이스 구현을 위한 window 및 view 아키텍처, 앱에 멀티 터치 및 기타 유형의 입력을 제공하는 이벤트 처리 인프라, 사용자, 시스템 및 앱 간의 상호 작용을 관리하는데 필요한 main run loop 를 제공합니다. 이 framework 가 제공하는 다른 기능에는 애니메이션 지원, 문서 지원, 그리기 및 인쇄 지원, 현재 장치에 대한 정보, 텍스트 관리 및 디스플레이, 검색 지원, 접근성 지원, 앱 확장 지원 및 리소스 관리가 포함됩니다.

> **Important**
>
> UIKit 클래스들은 앱의 main thread 또는 main dispatch queue에서만 사용해야 합니다. 이 제약은 특히 UIResponder에서 파생된 클래스 또는 사용자 인터페이스를 어떤 방식으로든 조작하는데 사용되는 클래스에 적용됩니다. 

## Curriculum

- [ Developer/Documentation/UIKit](https://developer.apple.com/documentation/uikit) 경로의 문서를 따릅니다.

- 일단 하나의 Component 씩 차근차근히 읽어나갈 계획입니다. 

- 각 Component 별로 Summary한 내용들을 기록할 계획입니다.

- 개인적인 스터디 + 추후 틈틈히 챙겨볼 handbook 목적입니다.

- **Topic I: First Steps**

  > | Ch#  | Chapter Subject                                              | Description                                        | Note                                                         |
  > | ---- | ------------------------------------------------------------ | -------------------------------------------------- | ------------------------------------------------------------ |
  > | 1    | **About App Development with UIKit** <p> UIKit과 앱 개발하기 | iOS 및 tvOS 앱을 위한 UIKit과 Xcode 기본 지원 학습 | [원문문서](https://developer.apple.com/documentation/uikit/about_app_development_with_uikit) |

- **Topic II: App Structure**

  > | Ch#  | Chapter Subject                         | Description                                                  | Note                                                         |
  > | ---- | --------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
  > | 2    | **Core App**                            | 앱의 데이터 모델 및 시스템간 상호작용 관리                   | [원문문서](https://developer.apple.com/documentation/uikit/core_app) |
  > | 3    | **Resource Management** <p> 리소스 관리 | 메인 실행 파일 외부에 저장한 image, string, storyboard, nib file 관리하기 | [원문문서](https://developer.apple.com/documentation/uikit/resource_management) |
  > | 4    | **App Extensions**                      | 시스템 외부에 앱 기본 기능 확장하기                          | [원문문서](https://developer.apple.com/documentation/uikit/app_extensions) |

- **Topic III: User Interface**

  > | Ch#  | Chapter Subject           | Description | Note                                                         |
  > | ---- | ------------------------- | ----------- | ------------------------------------------------------------ |
  > | 5    | **Views and Controls**    |             | [원문문서](https://developer.apple.com/documentation/uikit/views_and_controls) |
  > | 6    | **View Controllers**      |             | [원문문서](https://developer.apple.com/documentation/uikit/view_controllers) |
  > | 7    | **View Layout**           |             | [원문문서](https://developer.apple.com/documentation/uikit/view_layout) |
  > | 8    | **Animation and Haptics** |             | [원문문서](https://developer.apple.com/documentation/uikit/animation_and_haptics) |
  > | 9    | **Windows and Screens**   |             | [원문문서](https://developer.apple.com/documentation/uikit/windows_and_screens) |

- **Topic IV: User Interactions**

  > | Ch#  | Chapter Subject                    | Description | Note                                                         |
  > | ---- | ---------------------------------- | ----------- | ------------------------------------------------------------ |
  > | 10   | **Touches, Presses, and Gestures** |             | [원문문서](https://developer.apple.com/documentation/uikit/touches_presses_and_gestures) |
  > | 11   | **Drag and Drop**                  |             | [원문문서](https://developer.apple.com/documentation/uikit/drag_and_drop) |
  > | 12   | **Pencil Interactions**            |             | [원문문서](https://developer.apple.com/documentation/uikit/pencil_interactions) |
  > | 13   | **Focus-based Navigation**         |             | [원문문서](https://developer.apple.com/documentation/uikit/focus-based_navigation) |
  > | 14   | **Peek and Pop**                   |             | [원문문서](https://developer.apple.com/documentation/uikit/peek_and_pop) |
  > | 15   | **Keyboard and Menus**             |             | [원문문서](https://developer.apple.com/documentation/uikit/keyboard_and_menus) |
  > | 16   | **Accessibility**                  |             | [원문문서](https://developer.apple.com/documentation/uikit/accessibility) |

- **Topic V: Graphics, Drawing, and Printing**

  > | Ch#  | Chapter Subject    | Description | Note                                                         |
  > | ---- | ------------------ | ----------- | ------------------------------------------------------------ |
  > | 17   | **Images and PDF** |             | [원문문서](https://developer.apple.com/documentation/uikit/images_and_pdf) |
  > | 18   | **Drawing**        |             | [원문문서](https://developer.apple.com/documentation/uikit/drawing) |
  > | 19   | **Printing**       |             | [원문문서](https://developer.apple.com/documentation/uikit/printing) |

- **Topic VI: Text**

  > | Ch#  | Chapter Subject            | Description | Note                                                         |
  > | ---- | -------------------------- | ----------- | ------------------------------------------------------------ |
  > | 20   | **Text Display and Fonts** |             | [원문문서](https://developer.apple.com/documentation/uikit/text_display_and_fonts) |
  > | 21   | **Text Storage**           |             | [원문문서](https://developer.apple.com/documentation/uikit/text_storage) |
  > | 22   | **Keyboards and Input**    |             | [원문문서](https://developer.apple.com/documentation/uikit/keyboards_and_input) |

## Contact Me

- 📱 +82 10.3316.1609
- 📧 iosdeveloperkr@gmail.com

------

***Life is a game. Play it :)***