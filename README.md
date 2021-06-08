# sm_report
스마트모바일프로그램설계 최종 보고서

01주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week01   
02주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week02   
03주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week03   
04주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week04   
05주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week05   
06주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week06   
07주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week07   
08주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week08   
09주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week09   
10주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week10   
11주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week11   
12주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week12   
13주차 팀 프로젝트 활동 : https://github.com/Kim-KyungJin/sm_week13   

***

### 팀 구성   
스마트정보통신공학과 201621216 이준석   
스마트정보통신공학과 201921036 김경진   
스마트정보통신공학과 201921054 박유리   
스마트정보통신공학과 201921083 이혜정   
스마트정보통신공학과 201921104 홍수빈    
스마트정보통신공학과 201990009 미르자크메더브 사르더르    

***

#### 1. 주제 선정   
<pre>
저희 팀은 "통장 맞춤 추천"을 팀 프로젝트 주제로 선정하였습니다.
커플 혹은 친구들끼리 놀러갈 때나 여행할 때 주변에 놀만한 곳, 맛있는 음식이 있는 곳을 찾기 힘들 때를 대비하여
정해진 예산과 지역, 목적을 입력하여 주변에서 가장 가까운 곳, 혹은 목적과 가장 유사한 곳을 추천해주는 앱입니다.
</pre>

#### 2. 앱 이름   
<pre>
저희 팀은 이번 프로젝트 이름을 "어디 가게?"라고 지었습니다.
목적에 맞게 필요한 것을 추천하는 앱이므로 “어디에 위치한 가게”라는 뜻과
“어디 가게?” 라는 물음을 가진 “어디가게?” 를 프로젝트 앱 이름으로 정하게 되었습니다.
</pre>

#### 3. 앱 로고   
앱을 상징하는 로고 제작 과정을 링크에 담았습니다.   
https://github.com/Kim-KyungJin/sm_week03/blob/AppLogo/README.md  
    
![어플 2차 최종(확정)](https://user-images.githubusercontent.com/57963888/111958828-0e081080-8b31-11eb-92ba-2386b7edae8f.png)
![배경 최종(확정)](https://user-images.githubusercontent.com/57963888/111959121-63dcb880-8b31-11eb-85d9-a2c3607e9139.png)   

최종적으로 결정된 앱 로고 / 배경 디자인입니다.   

#### 4. 앱 기능   
<pre>
1. 로그인 기능을 넣어 이메일 인증을 한 사용자만 앱을 이용할 수 있도록 하였습니다.
2. 회원가입을 할 때, 일반인인지 업주인지 체크를 하여 일반인과 업주의 기능을 다르게 설정하였습니다.
3. 비밀번호 찾기 기능을 넣어 비밀번호를 잊어버렸을 때, 쉽게 찾을 수 있도록 설정하였습니다.
4. 마이페이지에서 개인정보를 수정할 수 있습니다. (이름, 비밀번호)
</pre>
<pre>
- 일반 회원
1. 지역과 예산, 목적을 설정하면 설정된 값에 맞추어 가게를 필터링하여 사용자가 원하는 목적에 맞는 가게들을 추천합니다.
2. 사람들이 많이 사용한다고 생각하는 음식점, 카페, 주점, 쇼핑, 기타로 설정했으며 이후에 더 추가될수도 있습니다.
3. 사용 가능한 예산과 해시태그 기능을 사용하여 사용자의 목적과 유사한 추천목록을 제공합니다.
4. 게시판을 생성하여 유저들 간의 소통이 활발하게 이루어지도록 만들었습니다. (ex. 맛집 추천, 영화 리뷰, 같이 밥 먹을 사람 구하기 등)
5. 처음 회원가입하고 로그인을 할 때, 지역과 예산을 설정하는 창이 뜨며 이후에는 마이페이지에서 설정을 변경할 수 있습니다.
6. 추천하는 가게 대신, 사용자가 직접 검색을 하여 원하는 가게를 찾을 수 있습니다.
7. 추천된 가게를 누르면 메뉴, 주소 등의 자세한 정보가 나옵니다.
</pre>
<pre>
- 업주 회원
1. 가게를 등록하고 메뉴를 등록하여 일반 회원이 가게를 볼 수 있습니다.
2. 처음 회원가입하고 로그인을 할 때, 가게의 이름과 종류, 주소 등을 설정하는 창이 뜨며 이후에는 마이페이지에서 설정을 변경할 수 있습니다.
3. 메인화면에서 자신이 등록한 가게와, 메뉴의 정보를 볼 수 있으며 언제든지 수정이 가능합니다.
4. 일반 회원과 같이 게시판에 글을 쓰고 소통할 수 있습니다.
5. 일반 회원과 같이 사용자가 검색을 하여 주변 가게들의 정보를 확인할 수 있습니다.
</pre>

#### 5. 앱 차별성   
<pre>
다른 앱과의 비교를 위해 구글 플레이 스토어에 가보았습니다.
주변 가게들을 추천해준다는 점에서 "구글맵", "카카오맵", "네이버 지도" 등이 유사했습니다.
또한, "동네가게"라는 앱에서 동네를 설정하여 주변 가게를 추천해주는 기능이 유사했습니다.

저희는 이 앱들과 차별성을 두기 위해 예산과 필터링 기능을 사용하였습니다.
예산을 설정하고 예산을 사용할 가게 비율 등을 설정하여 자신에게 맞는 추천 리스트가 뜨도록 설정했다는 점에서 다른 앱과의 차별성을 두었습니다.
또한, 동네를 인증하여 사용하는 앱과 달리 이 앱의 목적은 놀러가는 사람들에게 집중된 기능이므로 동네를 인증하지 않고도 미리 그 지역 주변의 가게들을 둘러볼 수 있습니다.
</pre>

#### 6. 앱 UI 디자인   
> 공통 화면   
> 
> ![KakaoTalk_20210608_214125728](https://user-images.githubusercontent.com/57963888/121195704-ccbf0b80-c8aa-11eb-9547-f2b04520c78d.png)
>![KakaoTalk_20210608_214125728_01](https://user-images.githubusercontent.com/57963888/121195720-cfb9fc00-c8aa-11eb-8406-98169f84589d.png)
>![KakaoTalk_20210608_214311023](https://user-images.githubusercontent.com/57963888/121197353-3390f480-c8ac-11eb-8972-eb55240538e0.png)   
>![KakaoTalk_20210608_214311023_01](https://user-images.githubusercontent.com/57963888/121197356-34c22180-c8ac-11eb-9a00-1a074d49685a.png)
>![KakaoTalk_20210608_225300794](https://user-images.githubusercontent.com/57963888/121197519-56bba400-c8ac-11eb-9c14-3839ef1cdfff.png)
>![KakaoTalk_20210608_214311023](https://user-images.githubusercontent.com/57963888/121197368-368be500-c8ac-11eb-9e97-dcce1417b4ba.png)   
>
 
>
> 일반 회원   
> 
>![KakaoTalk_20210608_214311023_03](https://user-images.githubusercontent.com/57963888/121197784-908caa80-c8ac-11eb-9eae-ef1c31b66a2f.png)
>![KakaoTalk_20210608_214311023_04](https://user-images.githubusercontent.com/57963888/121197788-91bdd780-c8ac-11eb-8990-4cb5d5319908.png)
>![KakaoTalk_20210608_211531908](https://user-images.githubusercontent.com/57963888/121196020-17d91e80-c8ab-11eb-9f61-d899cf32dfcb.png)   
>
>![KakaoTalk_20210608_224452798](https://user-images.githubusercontent.com/57963888/121196159-363f1a00-c8ab-11eb-8031-2b1ea3e8c1c0.png)
>![KakaoTalk_20210608_214125728_05](https://user-images.githubusercontent.com/57963888/121196178-3a6b3780-c8ab-11eb-92ce-d76198a6e6a9.png)
>![KakaoTalk_20210608_224824115](https://user-images.githubusercontent.com/57963888/121197918-ad28e280-c8ac-11eb-9d8d-469184b3d81c.png)   
>
>![KakaoTalk_20210608_213846476_01](https://user-images.githubusercontent.com/57963888/121197985-bb76fe80-c8ac-11eb-9eee-25d0fc790c09.png)
>![KakaoTalk_20210608_213846476_02](https://user-images.githubusercontent.com/57963888/121198004-bfa31c00-c8ac-11eb-8377-66fc7389a8dc.png)   
>
>![KakaoTalk_20210608_213846476_04](https://user-images.githubusercontent.com/57963888/121198023-c467d000-c8ac-11eb-928e-731822386fb6.png)
>![KakaoTalk_20210608_213846476_05](https://user-images.githubusercontent.com/57963888/121198031-c598fd00-c8ac-11eb-93ed-8a440502238b.png)
>![KakaoTalk_20210608_213846476_06](https://user-images.githubusercontent.com/57963888/121198045-c893ed80-c8ac-11eb-833a-135a799cf12a.png)
>![KakaoTalk_20210608_213846476_07](https://user-images.githubusercontent.com/57963888/121198072-ce89ce80-c8ac-11eb-9524-e2b04ee34be9.png)
>![KakaoTalk_20210608_213846476_08](https://user-images.githubusercontent.com/57963888/121198079-cfbafb80-c8ac-11eb-8597-39785591cb9d.png)
>![KakaoTalk_20210608_213846476_09](https://user-images.githubusercontent.com/57963888/121198081-d0539200-c8ac-11eb-85f4-8b76162ac037.png)   
>



#### 7. 앱 수익 창출   
<pre>
저희는 수익을 창출하기 위해 메인화면에서 마이페이지로 넘어가는 버튼을 눌렀을 때,
전면 광고가 뜨도록 설정하였습니다.
</pre>
![KakaoTalk_20210608_211531908](https://user-images.githubusercontent.com/57963888/121183228-d17dc280-c89e-11eb-9023-bfb9cd4c48a9.png)
![KakaoTalk_20210608_211210902](https://user-images.githubusercontent.com/57963888/121182860-74820c80-c89e-11eb-9471-c4d4807ed082.png)
![KakaoTalk_20210608_211210902_01](https://user-images.githubusercontent.com/57963888/121182870-75b33980-c89e-11eb-98c6-b29708db9196.png)
![KakaoTalk_20210608_211531908_01](https://user-images.githubusercontent.com/57963888/121183231-d2aeef80-c89e-11eb-9215-2f19088fa0e5.png)   


#### 8. 앱 실행 영상   


> 일반 회원 계정   
>> grace8362@naver.com   
>> a12345

> 업주 회원 계정   
>> study201921104@gmail.com   
>> 123456

#### 9. 아쉬운 점   
<pre>
저희가 구현하고자 했던 기능 중에 하나였던 GPS가 원래는 사용자의 위치를 자동적으로 받아와 그 지역 주변의 가게를 서치해주는 기능이였데,
그 기능 구현에 어려움이 있어 자동이 아닌 수동으로 사용자가 직접 자신의 위치를 spinner로 불러와 그 지역 근처의 가게들을 제공해주는 기능으로 변경하였습니다.
그리고 프로젝트 주제를 선정할 때 저희 앱의 테마 주제였던 "통장 맞춤"의 기능을 구현하기 위해 은행 어플과 연동을 시키고자 하였으나
시간 부족으로 다른 주요 기능들을 먼저 구현하고자 하여 추가하지 못하였습니다. 
또한, 시간 부족으로 해결하지 못한 기능이 수익 창출 방법을 위해 위의 전면 광고 뿐만 아니라 앱 내 결제 방식으로 수익을 창출하려고 하였으나
이 기능 또한 마지막까지 해결하지 못한 부분이 아쉽습니다.
</pre>
