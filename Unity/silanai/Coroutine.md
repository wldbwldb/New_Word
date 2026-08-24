## Coroutine

update 사이에 끼워넣어지면서 update는 안막는? 애니 사이에 1프래임씩 광고 넣어서 하는 다른 만화? 그런느낌

메서드 만들떄 return값에 IEnum 어쩌고 넣으면 되고 return 이 끝이 아니라 그냥 시간지연 같ㄴ은 기능중 하나로 작동한다

그냥 메서드는 작동 다하고update가 되는데 얘는 update하면서 동시에 않끊기고 되는게 짱 신기하다

그리고 얘는 작동이; 그냥 이름() 이 아니라 StartCoroutine(이름()) 해야 작동한다, StartCoroutine(이름(변수)) 도 된다

얘를 update대용으로 쓸수도 있다고