### fieldset
- 필드셋 요소는 웹 양식의 여러 컨트롤과 레이블(label)을 묶을 때 사용한다.

###  legend
- 레전드 요소는 부모 fieldset콘텐츠의 설명을 나타낸다.

### select
- css로 수정이 어렵다고 함
- 속성
    - multiple - 다중선택
    - autofocus
    - 조상 중 form 요소 있으면 해당 form과 연결됨
    
### option
- 속성
    - selected - 기본 선택
    - disabled - 선택할 수 없음
        
### optgroup 
- option 묶을때 사용
- 속성 
    - label - 필수 (그러나 option아니므로 선택할 수 없음)
    - disable - 하위 그룹 모두 선택할수 없음

### label
- label을 input과 연결시키려면 input에 id 달고 label에 for 속성 넣어야함
- label안에 input 중첩시키면 for , id 필요없음
- label 안에는 button이나 a 태그 넣지 말기 

