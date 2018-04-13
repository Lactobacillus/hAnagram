# hAnagram
## 이 세상 모든 애너그램을 하나로

애너그램을 만드는 프로그램

길이 n 인 문자열이 뒤섞일 수 있는 경우의 수는 아래와 같이 주어진다.
* 공백이 추가되어 여러 문자열로 쪼개지는 상황도 고려 (William Shakespeare => I am a weakish speller)
* 알파 i 는 i 번째 알파벳의 개수를 의미

![cn](http://latex.codecogs.com/gif.latex?%5Chuge%20c%28n%29%20%3D%20%5Cfrac%7Bn%21%20%5Ctimes%202%5E%7Bn-1%7D%7D%7B%5Cprod_%7Bi%3D1%7D%5E%7B26%7D%5Calpha_%7Bi%7D%7D)

이중 가장 그럴싸한 단어만 추려낼 방법은 무엇일까?

그럴싸한 단어만 추린 다음에, 영어 사전에 존재하는지 확인하면 될 텐데~