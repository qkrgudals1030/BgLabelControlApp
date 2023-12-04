### 사용자 정의 컨트롤을 활용한 실습

### 결과화면

![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/6638e511-d92f-458f-882a-582eb3b3e327)

교수님께서 올리신 사이트를 참고하여 빨간색 배경에서 초록색 배경으로 변경 후 I Love Anu를 입력해 보았습니다. 


### 1. 실습 과정
빈앱을 만들어 줍니다. (BgLabelControlApp)


### 사용자 정의 컨트롤 추가해주기

![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/35335589-e8cf-4095-bed3-b2a7df16ce87)

![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/103a394e-a522-4582-a240-4e7cb626d4c9)

만들어 주게 되면 3개의 파일이 생성됨

### 사용자 정의 컨트롤 클래스 구현

![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/40dfe5a7-8130-4da8-b488-dde40b3f02e9)


![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/ee6679ee-35f8-4c2c-81cc-3c2430a90a0a)


![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/bf4f3c8a-fa24-4be9-86bb-012d5cec0526)


해당되는 코드를 비교에서 삽입


### BgLabelControl의 기본 스타일 정의

![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/542c4630-9e72-4081-abb2-86fc5e1fbe07)


솔루션 탐색기에서 모든 파일표시를 해준후 프로젝트 노드 아래에 새폴더르 만들고 이름을 themes로 지정후 아래에 Resource Dictionary(WinUI) 유형의 새 항목을 추가 하고 이름을 "Generic.xaml"로 지정합니다.


### 기본 UI페이지에 BgLabelControl 인스턴스 추가


![image](https://github.com/qkrgudals1030/BgLabelControlApp/assets/50895124/3a53a72d-8c7b-485c-9167-2301a5101f79)


예제에서는 빨간색이였지만 초록색배경에 문구를 넣는것이기때문에 초록색배경에 I LOVE Anu를 입력하였습니다. 
