<div align="center">
  
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=FaceDetection_Counting&fontSize=50" />
  
</div>

  * 해당 프로젝트는 **개인프로젝트** 입니다.

  <br/>

<div align="center">
  
  ### [프로젝트 개요]
  <img src=https://user-images.githubusercontent.com/37567501/174423209-69e83f82-3846-48f3-901e-20f40ec46e4a.png width="850" height="400"/>
  
  <br/><br/>
  ---
  <br/><br/>
  
  ### [수행과정]
  <img src=https://user-images.githubusercontent.com/37567501/174423407-225cb43d-5391-4ab0-a683-4f7103b216e2.png width="850" height="400"/>
  <img src=https://user-images.githubusercontent.com/37567501/174423431-e9cee59c-03d2-4f51-8b43-2c32080a8302.png width="850" height="400"/>
  <img src=https://user-images.githubusercontent.com/37567501/174423454-cbe9b891-a6cd-42a9-b86a-35492775015d.png width="850" height="400"/>
  
</div>

  > **얼굴 추적 원리**
  
  : 이전 프레임에서 얼굴로 확인된 박스와 현재 프레임에서 가장 가까운 위치에 있는 박스의 **이미지 유사도를 측정**하여 같은 ID 값임을 확인
  
  <br/>
  
<div align="center">
  
  <img src=https://user-images.githubusercontent.com/37567501/174423481-ec3adad0-9679-4b84-84c8-9161bceda2a3.png width="850" height="400"/>
  <img src=https://user-images.githubusercontent.com/37567501/174423497-2e09a048-1abf-4d35-a05b-47c2ee5b1819.png width="850" height="400"/>
  
  <br/><br/>
  ---
  <br/><br/>
  
  ### [수행결과]
  ![image](https://user-images.githubusercontent.com/37567501/174423552-53b2ac8b-fc58-4b81-90f5-f27023fcc6cd.png)
  
  **[설명]**
</div>

1. 얼굴 인식 후 빨간 박스 생성(+개인정보 보호를 위해 모자이크 처리)

2. 얼굴 인식 박스별 고유ID 값을 박스 센터에 할당

3. 고유ID 값이 중앙 빨간선(Counting Line)을 오른쪽에서 왼쪽으로 이동하면 화면 좌측 하단에 인원수가 +1 증가

<div align="center">
  
  <br/><br/>
  ---
  <br/><br/>
  
  ### [개선사항]
  해상도가 떨어지면 얼굴 인식률이 떨어지는 문제점 발생 **다양한 얼굴 표본을 추가 학습**하여 해결이 필요함
    
  <br/><br/>
  ---
  <br/><br/>
    
  ### [활용방안]
  **출입인원 파악**과 손님이 **머물렀던 시간** 등을 정보화하여 <span style="color:red">**마케팅에 활용**</span> 가능
  
  
  ![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=footer)
</div>
