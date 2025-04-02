# 생성형 인공지능을 활용한 이미지 분류 프로젝트
#### 마크다운 방법
### 구리고등학교
## 1학년
![스크린샷 2025-04-02 155653](https://github.com/user-attachments/assets/6424c412-e33d-476a-9b0f-b979b6c7cbb1)
1.구구단 만들기
```bash
for i in range(2, 10):  
    print(f"\n[{i}단]")
    for j in range(1, 10):  
        print(f"{i} × {j} = {i * j}")
입력받아 구구단 표시하기
'''bash
dan = int(input("출력할 구구단을 입력하세요 (3 이상의 숫자): "))

# 입력값이 3 미만이면 오류 메시지 출력
if dan < 3:
    print("입력한 숫자가 3 미만입니다. 다시 입력하세요.")
else:
    print(f"\n[{dan}단]")
    for i in range(1, 10):
        print(f"{dan} × {i} = {dan * i}")
