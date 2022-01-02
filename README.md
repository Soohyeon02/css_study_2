# Today's study :)
- CSS 의 텍스트 꾸미기 속성, display 와 border 에 대해서 공부했음

<텍스트 꾸미기 속성>

    font-family : 글꼴을 정의
    font-size : 글자 크기 정의
    text-align : 정렬 방식 정의
    color : 글자 색상 정의
    
<font-family>

    font-family : 글꼴을 지정할 수 있는 속성이며, 여러 글꼴을 연달아 기입하여 우선순위 지정
    TImes 글꼴을 우선 지정하되, 지원되지 않을 경우 monospace 를 지정함

<font-size>

    font-size : 수치와 단위를 지정해 글자의 크기를 정의할 수 있다.
    <단위>
    1. px : 모니터 상의 화소 하나 크기에 대응하는 절대적인 크기 => 절대값
    2. rem : <html> 태그의 font-size 에 대응하는 상대적인 크기 => 상대값
    3. em : 부모태그(상위태그) 의 font-size 에 대응하는 상대적인 크기 => 상대값
    
<text-align>
    
    text-align : 블록 내에서 텍스트의 정렬 방식을 정의한다. 미리 정의된 키워드 값을 지정
    <속성값>
    1. left / right : 왼쪽 또는 오른쪽 정렬
    2. center : 가운데 정렬
    3. justify : 양끝 정렬(마지막 줄 제외)
    
<color>

    color : 텍스트의 색상을 정의함. 다양한 방법을 색상을 지정
    <키워드 유형>
    1. 키워드 : 미리 정의된 색상별 키워드를 사용한다(ex. red, blue)
    2. RGB 색상 코드 : # + 여섯자리 16진수 값 형태로 지정 (ex. #000000)
    3. RGB 함수 : Red, Green, Blue 의 수준을 각각 정의해 지정 (ex. rgb(100%, 0%, 0%))
    
<요소 복습>

    블록 레벨 요소 : 자기가 속한 영역의 너비를 모두 차지하여 블록을 형성
    (ex. div, p, h1 등)
    인라인 요소 : 자기에게 필요한 만큼의 공간만 차지
    (ex. span, a 등)

<display 속성>

    display 속성 : 요소를 블록과 인라인 요소 중 어느 쪽으로 처리할지 정의
    ex) div{ display: inline; } or a{ display: block; }
    
<display 속성 값>

    inline : 인라인으로 처리
    block : 블록 레벨로 처리
    inline-block : 인라인으로 배치하되, 블록 레벨 요소의 속성을 추가할 수 있도록 처리
    none : 디스플레이(표시) 하지 않는다.
    
<bolder 속성>

    border 속성 : border 속성은 요소가 차지하고 있는 영역에 테두리를 그릴 수 있음
    border 속성에는 속성값으로 테두리의 두께, 모양, 크기 등을 함꼐 지정할 수 있는데
    이러한 속성을 '단축속성' 이라 한다.
    
<border 속성의 하위 속성>
    
    1. border-color : color 정의 방식과 동일
    2. border-width : thin, medium, thick 등의 키워드 또는 px, em, rem 등의 단위
    3. border-style : none(기본값), solid(직선), dotted(점선), dashed(긴 점선) 등
    
    
### 알게 된 점
- display 속성은 요소의 불록 레벨, 인라인 여부를 변경 처리 가능
- display 속성은 요소를 배치할 레이아웃을 결정할 때도 사용
- border 속성은 요소가 차지하는 영역에 테두리를 그릴 수 있음
- border 는 여라가지 속성을 함께 정의할 수 있는 '단축속성'이다.
- border 의 하위 속성은 border-style, border-width, border-color 임

### 다음 단계
- CSS 를 빠르게 공부하고 JavaScript 로 넘어가야 한다.
- 내일부터 익스턴십이 시작될텐데 많이 부족하지만 열심히 공부하면서 성장해야겠다!

**2022.01.02.**
