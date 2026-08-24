### 코드 스멜

의역 조금하면 냄새나는 코드, 구린내 난다고

뭔뜻일지 생각해보기도 전에 걍 Ai가 말해줌

- 일단 겉으로는 문제없는데 높은 확률로 썩어 업데이트를 하던 뭘하던 반드시 문제가 생길 코드
- 역활은 유지한채 정리를 한번 싹 해서 문제 생길 부분을 없애야한다
- 종류가 여러개다
 
    1. 중복 코드(지워)
    1. Long Method (쓸데없이 긴 메서드(쪼개고 이름 바꾸고 클래스 추출+조건문 쪼개기))
    1. Long Parameter List (쓸데없이 매개변수 많이 쓰는 메서드(메서드 채로 그냥 가져다주기))
    1. Divergent Change (하나 계속 고쳐쓰기(클래스 추출이 뭐여))
    1. Shotgun Surgery (흩어진 기능(사혼의 구슬?))
    1. Feature Envy (다른 클래스 자꾸 건드리는 메서드(호적 바꿔라))
    1. Swtich Statements (스위치 과다(개선 기법 : 메서드 추출(Extract Method), 메서드 이동(Move Method), 분류 부호를 하위 클래스로 전환(Replace Type Code with Subclasses), 분류 부호를 상태/전략 패턴으로 전환(Replace Type Code With State/Strategy)(모르겠으니 일단 복븉)))
    1. Magic Number(이러면 니 후임은 어쩌ㅗ라고( final 또는 const와 같은 변수 상수화 키워드로 상수를 변수로 네이밍 하여 의도를 표현()태그 잘 붙여라))