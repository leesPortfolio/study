# 미니 프로젝트

- ### MvpExamApp 설명

  - MFC 게임이 끝난후 사용자가 아이디를 입력하면 서버에 아이디와 점수가 기록되고 안드로이드에서는 이러한 정보를 확인할 수 있습니다. MFC 사용자가 게임이 끝난 후 메시지를 입력 하고 전송 버튼을 누르면 서버에서 retrofit2을 통해(api key 빼놓았습니다) 전송 내용을 가지고 firebase에 fcm 전송을 요구하면 앱에서는 이러한 메시지 내용을 Notification을 통해 확인 할 수 있습니다.