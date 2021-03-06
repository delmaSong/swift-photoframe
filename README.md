# 사진액자 앱



## Step1 - Tabbed App

- repository fork / clone 후 tabbed app 템플릿의 프로젝트 생성
- `print(#file, #line, #function, #column)` 수행

<img src="https://user-images.githubusercontent.com/40784518/73708250-33756780-4741-11ea-81c2-41d338082c20.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73708290-4a1bbe80-4741-11ea-923f-7c785bf20149.png" width="30%"></img>



## Step2 - IBOutlet

- `First Scene` 의 레이블을 IBOutlet으로 연결
- 연결한 아웃렛 변수에 값을 변경
- 레이블 속성 변경 

<img src="https://user-images.githubusercontent.com/40784518/73643455-e2209600-46b6-11ea-8622-93676dcb80e6.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73646679-4a727600-46bd-11ea-98f8-f576e10997ca.png" width="30%"></img>



## Step3 - IBAction

- `First Scene` 에 버튼(UIButton)을 추가하고 IBAction으로 연결
- 연결한 액션에 대한 메서드 구현

<img src="https://user-images.githubusercontent.com/40784518/73707948-4a678a00-4740-11ea-9651-9230bca8c16b.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73708076-afbb7b00-4740-11ea-8395-72e7041abb61.png" width="30%"></img>



## Step4

- 새로운 Scene과 Segue 추가

<img src="https://user-images.githubusercontent.com/40784518/73715011-f23b8280-4755-11ea-8d77-4b70f6dce172.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73715088-2d3db600-4756-11ea-922e-93770297ee3f.png" width="30%"></img>





## Step5 - View Controller

- 스토리보드 구성 요소와 클래스 코드와 연결해서 동작을 확장한다.
- View Controller Life Cycle 학습
  - viewWillAppear()
    - view가 나타나기 시작할 때 수행
  - viewDidAppear()
    - view가 다 나타나고 나면 수행
  - viewWillDisappear()
    - view가 사라지기 시작할 때 수행
  - viewDidDisappear()
    - view가 사라지고 나면 수행

<img src="https://user-images.githubusercontent.com/40784518/73719028-7d6e4580-4761-11ea-8801-0c2626fdf87e.png" width="30%"></img>



## Step6 - Container ViewController

- 내비게이션 컨트롤러(Navigation Controller)를 Embed 시켜서 동작하도록 개선

  

<img src="https://user-images.githubusercontent.com/40784518/73721169-ffad3880-4766-11ea-9429-db01e0d72eca.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73721207-1784bc80-4767-11ea-978c-d1eb4443b285.png" width="30%"></img>





## Step7 - Second Scene 화면

- `Second Scene`에 `UIImageView` 추가
- `다음` 버튼 클릭 시 이미지 랜덤하게 변경되는 기능 추가

<img src="https://user-images.githubusercontent.com/40784518/73725045-f6749980-476f-11ea-9346-8a7fba6c47b9.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73725373-96322780-4770-11ea-8ca3-e7d32edd80b8.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73725414-aba75180-4770-11ea-9543-867c897fa953.png" width="30%"></img>





## 추가 요구사항

- `Second Scene`  에 액자 이미지 추가 
- `선택`  버튼으로 사진 앱 - 카메라롤 이동 
- 사진 선택시 image view에 선택된 이미지 추가

<img src="https://user-images.githubusercontent.com/40784518/73731313-9edc2b00-477b-11ea-94d9-876f62597a8a.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73731358-b2879180-477b-11ea-826a-7b1ace1a053c.png" width="30%"></img><img src="https://user-images.githubusercontent.com/40784518/73731408-c7642500-477b-11ea-9e77-b51e8d58759e.png" width="30%"></img>