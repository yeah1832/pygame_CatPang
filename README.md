# pygame_CatPang
인프런 < 파이썬 무료 강의 (활용편1) - 추억의 오락실 게임 만들기 (3시간) > 강의를 보고 간단한 슈팅게임을 만들어 보았습니다!

참고한 게임은 아래와 같으며, 캐릭터가 무기를 쏴서 공을 맞추는 게임입니다.

![](https://images.velog.io/images/yeah7598/post/f52920b1-c643-48a6-b595-4cc99050ff7c/20.gif)

</br>

## Step1 배경과 캐릭터 불러오기

![](https://images.velog.io/images/yeah7598/post/4176cf3a-7ae3-41bb-879c-5a679ee5f80c/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202022-01-24%20%E1%84%8B%E1%85%A9%E1%84%8C%E1%85%A5%E1%86%AB%206.26.40.png)

</br>

## Step2 무기와 키보드 이벤트 적용하기

![](https://images.velog.io/images/yeah7598/post/de8f3d52-68fc-4ee6-81b2-0754ad25563c/ezgif.com-gif-maker%20(1).gif)

</br>

무기 이미지를 불러와 적용하고, 키보드 방향키(이동), 스페이스키(무기 발사)에 이벤트를 적용합니다.

</br>

## Step3 공 생성 및 충돌 처리

공을 생성하고, 공과 무기가 만났을 때 여러 개로 쪼개지는 로직을 처리합니다.

![](https://images.velog.io/images/yeah7598/post/d6525f8f-ceea-4570-ab62-80a45f00907a/ezgif.com-gif-maker%20(2).gif)

</br>

## Step4 게임 오버 이벤트 적용

정해진 시간(100초)을 초과했을 경우 게임이 오버되도록 설정합니다.

![](https://images.velog.io/images/yeah7598/post/53134a26-501e-40ad-a6ca-1c28e9078321/ezgif.com-gif-maker%20(3).gif)
