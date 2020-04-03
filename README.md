# react-profile-11th 개발 프론트앤드 유현우

> 배포된 주소 : https://react-profile-11th.puba5.now.sh

## 미션 설명

[미션 설명](./docs/mission-description/README.md)

## 미션 제출 방법

[미션 제출 방법](./docs/how-to-submit/README.md)

## PR

> ### 제목 : [1주차] 유현우 미션 제출합니다. <br>
>
> ### 내용 : <br>
>
> 안녕하세요.
> 과제 진행하면서 중간중간에 모르는게 많아 그것들을 공부하느라 생각보다 시간이 많이 걸렸습니다. <br>
>
> 가장 처음에 에러난 것은 profile-card.js의 경로 문제였는데, React에서는 오류가 코드 어느 부분에서 오류가 났다!라고 뜨는 것도 있지만, 그냥 글로만 표시된다는 것을 알게 되었고, 이후 빌드할 때 오류를 좀 더 쉽게 해결할 수 있었던 것 같습니다. <br>
>
> 두 번째로 모르는 것이 나왔을 때는 zeit 배포할 때였는데, Next.js를 사용할 것인지 물어봐서 "나는 React를 하는데 왜 Next 사용하라고 하지?" 라는 의문을 품고 검색해보니 Nextjs는 React를 SSR으로 렌더링 해주는 프레임워크고, 그 렌더링된 것을 zeit으로 배포해준다는 것을 알게되었습니다. <br>
>
> 세번째 고비는 컴포넌트 하나만 만들고 컴포넌트 재활용을 어떻게 할지였습니다. 정확히 말하면 프로필 카드들은 4개가 반복되므로 이걸 어떻게 만들 수 있을까 고민했었습니다. 물론 4개를 직접 4번 적어줄 수 있었지만, Vue를 공부하면서 "컴포넌트에 for과 if를 사용할 수 있고, 이는 React와 비슷하다"라는 말이 기억나서 컴포넌트를 반복적으로 표현하는 방법을 찾아봤습니다. 다행히 component iteration이라 검색하니 바로 나왔지만, 정확한 개념적인 설명 없이 코드만 있는 설명만 많아서, map 함수를 사용하는 코드를 하나하나 이해하고 고쳐보면서 미션에 알맞게 수정하는게 약간의 고비였습니다. <br>
> 이때 React스러운 코드란 무엇인가 고민했었는데, 아직도 정확히 React스러운 코드가 무엇인지 확실하게 말하긴 어렵고 더욱 더 공부해봐야겠지만, React스러운 코드란
>
> 1. 컴포넌트를 만들어서 재활용할 수 있게 하는 것
> 2. 데이터를 상위 컴포넌트에서 하위 컴포넌트로 전달하는 것
> 3. 함수를 사용하여 컴포넌트들을 만드는 것
>
> 이라고 생각하여 최대한 이런 방식으로 짜도록 노력했습니다.
>
> 네번째 가장 오래 걸렸던 과정은 CSS...대충 큰 틀로 추상적으로 코드가 돌아가서, 데이터를 잘 띄우는 위의 단계까지는 그래도 얼마 걸리지 않고 금방했지만, 디자인을 그대로 맞추는 과정이 상대적으로 힘들었습니다. 사실 CSS는 기본 개념만 공부하고, 활용하는 것은 따로 배우지 않고 필요할 때마다 그때 그때 찾아봤었는데, 이번에 느낀 것은 이것도 좀 공부해야겠다고 느꼈습니다. 디자인 시안이 주어지면 그것을 자유자재로 만들어주어야하는데 CSS 모르면 삽질 좀 많이 할 것 같아서 시간이 나면 체계적?으로 배워야하는 필요성을 느꼈습니다. <br>
>
> 다섯 번째로는 선택 미션을 할 때 나이 순 배열이었는데, Javascript에서 배열을 선언할 때, const로 선언했음에도 불구하고 sort가 되는게 신기했습니다. 직관적으로는 const니까 순서도 안 바뀔 줄 알았는데 sort가 너무 잘 되서 문제 없이 선택 미션을 할 수 있었습니다. <br>
>
> 그리고 React 외적인 부분에서는 커밋이나 변수명 정하기 같은 부분을 정하기가 너무 어려워서 이 부분도 여러 경험을 쌓으면서 학습을 다짐하게 되었던 과제였습니다.

##추가사항

> 필수 결과 화면과 선택 결과 화면에서 "사진 크기" 같은 일부 디자인이 다른데, 이런 부분은 필수 결과 화면에 맞추어 올렸습니다.
