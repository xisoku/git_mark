# 데이터 분석 보고서 만들기

## 마크다운

마크다운 문법으로 코드를 작성해 [HTML](https://ko.wikipedia.org/wiki/HTML)로 변환할 수 있습니다. 마크다운을 이용하면 분석 과정과 결과를 자세하게 기술할 수 있어서 **재현 가능성**을 갖춘 *데이터 분석 보고서*를 만들 수 있습니다.

### 마크다운 문법 예제 

코드와 코드 실행 결과물을 보고서에 함께 출력합니다.

from PIL import Image

# 이미지 열기
img = Image.open('image.png')

# 이미지 출력
img