# Django Template 사용법

Django의 템플릿 시스템은 일반적인 HTML을 동적으로 변환해주는 강력한 기능을 제공합니다. HTML 내에 파이썬 코드를 사용하여 동적인 웹 페이지를 만들 수 있으며, 반복문, 조건문, 변수 표시, 상속 등의 기능을 활용할 수 있습니다.

## Django 템플릿과 일반 HTML의 차이점

1. **변수와 파이썬 코드 사용**:  
   Django 템플릿에서는 HTML 파일 안에 파이썬 변수와 로직을 사용할 수 있습니다. 일반적인 HTML은 정적이지만, Django 템플릿은 파이썬 뷰에서 전달된 데이터를 사용하여 동적으로 변환됩니다.

2. **템플릿 태그**:  
   Django 템플릿에서는 `{% %}`와 `{{ }}`를 사용해 HTML에서 파이썬 코드를 실행하거나 변수를 출력할 수 있습니다. 예를 들어, `{{ name }}`은 파이썬 변수 `name`의 값을 출력합니다.

3. **템플릿 상속**:  
   Django 템플릿은 상속을 지원하여 기본 레이아웃을 정의하고, 이를 재사용할 수 있습니다. 일반 HTML에서는 이 기능이 없어 동일한 코드가 중복되는 경우가 많습니다.

---

간단히 말해서 {} 안에 있으면, 그냥 html이 아니라, django와 관련된 녀석