# home-work
멋쟁이 사자 과제 n01 
HTML/CSS
<br>
<br>
### 1. 화면 설계
<img width="400" alt="image" src="https://github.com/1101x/homework/assets/121869052/0801d38d-c22a-4400-b220-b5b100178f39">
<br>
<br>
  
### 2. 마크업
1. 전체 컨텐츠 가운데 정렬을 위한 설정
```
.artboard{
  width: 502px;
  margin: 20px auto;
}
```  
2. 기본 설정(여백 삭제 등)

```
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-size: 100%;
  list-style-type: none;
  ;
}
```

3. 개별 박스 설정
```
    .box2 {
  background: white;
  border: 1px solid var(--gray-500);
  height: 310px;
  padding: 14px 24px;
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  position: relative;
}
```
4. 버튼 효과 설정
~~~
.bt-buy {
  border: none;
  color: white;
  position: absolute;
  left: 20px;
  bottom: 20px;
  width: 42px;
  height: 42px;
  display: flex;
  justify-content: center;
  align-items: center;

}
.bt-buy:hover::before{
  content: '구매하기';
  width: 144px;
  background: var(--blue);
}
~~~
