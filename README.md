# Text To Svg Tspan

## 해결하고자 하는 것, The problem 

* 문장에 SVG 그래픽 효과를 넣기 위해서 단어를 분리하고 좌표를 설정하고자 한다.
* In order to add SVG graphic effects to sentences, we want to separate words and set coordinates.

## 해결 순서, How to solve the problem
### KR
1. 대상 데이터를 줄 단위로 분리한다.
2. 각 줄을 공백 기준으로 분리하여 tspan으로 감싼다.
3. 뷰어 SVG 의 폭을 계산하여 폭 안에 모든 텍스트가 표현되도록 텍스트 좌표를 설정한다.
4. 뷰어의 높이를 재설정하고 뷰어에 표현한다.

### EN
1. Separate the target data into lines.
2. Separate each line by space and wrap it with tspan.
3. Calculate the width of the viewer SVG and set the text coordinates so that all text is expressed within the width.
4. Reset the height of the viewer and display it on the viewer.

