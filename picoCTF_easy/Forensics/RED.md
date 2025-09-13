## 문제 
RED 이미지 안에 숨겨진 정보를 찾아라

## 풀이 방법
RED 이미지를 보면 그냥 빨간 상자 하나만 보인다
zsteg을 이용하여 숨겨진 정보를 찾는다 
base64로 추측되는 문자가 보인다
반대로 복호화하면 flag 획득!

## 배운 점
steganography = 아예 보이지 않는 정보를 찾아내는 것
zsteg > steganography 기법 중 하나인 LSB 변조를 탐지해 PNG, BMP 같은 파일에서 숨겨진 데이터를 찾아냄
