# unity-tutorial
유니티로 앱 만들기

"공대생 옷입히기" 앱을 만들기 위한 발걸음

1. "Live Session: Making A Flappy Bird Style Game" 를 [3까지만](https://unity3d.com/kr/learn/tutorials/topics/2d-game-creation/bird-script?playlist=17093) 만들음

2. 안드로이드 sdk를 깔아서 안드로이드 apk로 만들어서 구동(까는데만 2시간)

3. 직접 안드로이드에서 실행해보고 `Input.GetMouseButtonDown` 함수는 터치에는 적용되지 않는다는 것을 깨달음

4. 기존 코드를 다음과 같이 수정함 <br>
`if(Input.GetMouseButtonDown (0))` -> `if(Input.GetMouseButtonDown (0) || Input.touchCount > 0)`

5. 폰에서 bird가 잘 날아가는 것을 [확인함](https://github.com/junsooo/unity-tutorial/blob/master/KakaoTalk_20190226_012940589.png)


