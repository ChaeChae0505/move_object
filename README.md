#### 1~6 실행
```python

fourcc = cv2.VideoWriter_fourcc(*'DIVX')

video = cv2.VideoWriter(video_name, fourcc, 22.5*33/31, (width,height))

```
위와 같이 수정 후 

실행시키면 되는데 뭔가 파일이 이상함 조금 수정 필요할 듯

[출처](https://sites.google.com/view/dailycoding00/main/PUGB_enemy?authuser=0)
### 수정 배포시 원작자 [일상코딩/dailycoding] 표시 必
