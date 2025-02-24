<img src="./docs/logo.svg" width="30000"/>

##

<div align="center">
   <a href="/ENGLISH.md"> <b>Translate to english</b> </a>
</div>
<br>

<div align = "center">  

<a href="https://github.com/devxb/gitanimals">
    <img src="https://render.gitanimals.org/lines/devxb?pet-id=23" width="25%" height="100"/><img src="https://render.gitanimals.org/lines/devxb?pet-id=22" width="25%" height="100"/><img src="https://render.gitanimals.org/lines/devxb?pet-id=1" width="25%" height="100"/>
</a>

⭐스타를 눌러주세요 개발에 큰 도움이 됩니다!⭐️<br>
<i><h4><a href="https://github.com/devxb/gitanimals/stargazers">Press star</a></h4></i>
</div>

<div align="center">
<h3>깃허브 활동으로 펫을 키우세요!</h3> 
<h4> 깃허브 활동으로 펫을 획득하고 성장시킬 수 있어요.
<br> 커밋을 30번 하면 1개의 펫을 추가로 입양할 수 있어요.
<br> 1개의 contribution은 랜덤한 펫의 level을 1 증가시켜요.
<br> 키운 펫은 다른사람과 거래할 수 있어요.     
<br>
<br>
50 종류가 넘는 펫을 뽑고 기르세요.
<br>

[홈페이지](https://gitanimals.org) 에서 펫을 거래하고 관리할 수 있어요.

</h4>
<br>
<a href="https://github.com/devxb/gitanimals">
    <img alt="docs/sample.svg" src="https://render.gitanimals.org/farms/devxb"/>
</a>
</div>

## 빠르게 사용하기

아래의 링크를 깃허브 Readme 에 붙여넣기 하는것으로 쉽게 적용할 수 있어요.

> [!IMPORTANT]   
> {username} 은 자신의 깃허브 닉네임 (ex. devxb) 으로 변경해주세요.    
> 이때, {username} 은 반드시 자신의 깃허브 이름이 들어가야 합니다.

### line mode

line mode는 자신이 갖고있는 펫중 하나를 지정해서, 지정한 width, height범위에서 움직이게 해요.   
line mode를 사용할때, markdown 방식으로 이미지를 요청하면, width, height를 설정할 수 없어서 펫이 보이지 않을 수 있으니, HTMl방식을
사용해주세요.

> [!TIP]   
> **Img의 width와 height를 조절해서 펫의 이동영역을 조절할 수 있어요.**   
> width를 길게 height를 작게하면 (width = 1000, height = 60) 가로로 길게 움직이게 할 수 있어요.   
> 반대로, width를 작게 height를 길게하면 (width = 60, height = 1000) 세로로 길게 움직이게 할 수 있어요.   
> 만약, 펫이 보이지 않는다면, img의 height를 펫의 세로 길이보다 충분히 크게 적용해주세요.


<a href="https://github.com/devxb/gitanimals">
    <img src = "https://render.gitanimals.org/lines/devxb?pet-id=1" width="300" height="120"/>
</a>

```html
<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/lines/{username}?pet-id=1" width="1000" height="120"/>
</a>
```   

_pet-id에 아무값도 입력하지 않으면, 첫번째 펫이 가져와져요._

변경 가능한 pet-id는 `https://render.gitanimals.org/users/{username}` 의 {username}을 자신의 깃허브 아이디로 변경 후 API를
요청하면 확인할 수 있어요.   
API 응답의 `$.personas.[].id` 에 해당하는 값을 pet-id에 입력하면 돼요.

lines모드에서는 펫 레벨 위에 총 contributions수를 보여줘요. 원하지 않을경우, 쿼리 파라미터로 `contribution-view=false`를 담아 요청하세요.

### farm mode

farm mode는 갖고있는 모든 동물과 추가적인 정보를 보여줘요.

<a href="https://github.com/devxb/gitanimals">
    <img src = "https://render.gitanimals.org/farms/devxb" width="300"/>
</a>

**html**

```html
<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/farms/{username}"/>
</a>
```

## TIPS

### 펫을 획득하는 방법

펫은 다음 두가지 방법으로 획득할 수 있어요.

1. **커밋 30번하기**    
   커밋이 30번 누적되면 새로운 펫이 등장해요. 이때, 모든 펫들은 등장하는 확률이 달라요.   
   이때, 최대로 얻을 수 있는 펫은 30개 입니다. 30개가 넘는 펫은 인벤토리로 들어가며, 홈페이지에서 언제든지 보여지는 펫과 교체할 수 있어요.
2. **펫 구매하기**    
   다른 유저가 판매하는 펫을 커밋포인트로 구매할 수 있어요.    
   커밋 1회당 일정량의 포인트가 지급됩니다. 혹은 자신의 펫을 판매해서 커밋포인트를 얻을수도 있어요.

### Total contributions

Total contribtuions 는 깃허브에 가입 후 집계된 Contribtuions 의 총합 이에요.    
_새로운 contribution은 반영은 최대 1시간이 소요될 수 있어요._

### 등장 가능한 펫들

| name                                                                                                     | ratio | Description                                                                                                                                                                  |
|----------------------------------------------------------------------------------------------------------|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| DESSERT_FOX <br> <img src = "docs/dessert-fox.svg" width="80px" height="65px"/>                          | 0.05  |                                                                                                                                                                              |
| RABBIT <br> <img src = "docs/rabbit.svg" width="40px" height="55px"/>                                    | 0.9   |                                                                                                                                                                              |
| MOLE <br> <img src = "docs/mole.svg" width="40px" height="45px" />                                       | 0.3   |                                                                                                                                                                              |
| MOLE_GRASS <br> <img src = "docs/mole-grass.svg" width="45px" height="45px" />                           | 0.1   |                                                                                                                                                                              |
| QUOKKA <br> <img src = "docs/quokka.svg" width="23px" height="42px" />                                   | 0.3   |                                                                                                                                                                              |
| QUOKKA_LEAF <br> <img src = "docs/quokka-leaf.svg" width="23px" height="42px" />                         | 0.1   |                                                                                                                                                                              |
| QUOKKA_SUNGLASSES <br> <img src = "docs/quokka-sunglasses.svg" width="23px" height="42px" />             | 0.05  |                                                                                                                                                                              |
| FISH_MAN <br> <img src="docs/fishman.svg" width="35px" height="75px"/>                                   | 0.001 |                                                                                                                                                                              |
| FISH_MAN_GLASSES <br> <img src="docs/fishman-glasses.svg" width="35px" height="75px" />                  | 0.001 |                                                                                                                                                                              |
| flamingo <br> <img src="docs/flamingo.svg" width="50px" height="110"/>                                   | 0.08  |                                                                                                                                                                              |
| TEN_MM <br> <img src="docs/tenmm.svg" width="80px" height="90px"/>                                       | 0.00  | Character created by `10MM` donations <br> Only buy in shop <br> <a href="https://github.com/depromeet/10mm-client-web"> 10MM </a>                                           |
| goblin <br> <img src="docs/goblin.svg" width="80px" height="80px"/>                                      | 0.06  |                                                                                                                                                                              |
| goblin-bag <br> <img src="docs/goblin-bag.svg" width="100px" height="80px"/>                             | 0.03  |                                                                                                                                                                              |
| bibbi <br> <img src="docs/bbibbi.svg" width="80px" height="100px"/>                                      | 0.00  | Character created by `BIBBI` donations <br> Only buy in shop <br> <a href="https://play.google.com/store/apps/details?id=com.no5ing.bbibbi&hl=es_PY&gl=US&pli=1"> BIBBI </a> |
| cat <br> <img src="docs/cat.svg" width="50px" height="70px"/>                                            | 0.1   |                                                                                                                                                                              |
| cheese-cat <br> <img src="docs/cheese-cat.svg" width="50px" height="70px"/>                              | 0.04  |                                                                                                                                                                              |
| galchi-cat <br> <img src="docs/galchi-cat.svg" width="50px" height="70px"/>                              | 0.06  |                                                                                                                                                                              |
| white-cat <br> <img src="docs/white-cat.svg" width="50px" height="70px"/>                                | 0.04  |                                                                                                                                                                              |
| goose <br> <img src="docs/goose.svg" width="100px" height="60px"/>                                       | 1.0   |                                                                                                                                                                              |
| goose_sunglasses <br> <img src="docs/goose-sunglasses.svg" width="100px" height="60px"/>                 | 0.05  |                                                                                                                                                                              |
| goose_kotlin <br> <img src="docs/goose-kotlin.svg" width="100px" height="60px"/>                         | 0.01  |                                                                                                                                                                              |
| goose_java <br> <img src="docs/goose-java.svg" width="100px" height="60px"/>                             | 0.01  |                                                                                                                                                                              |
| goose_js <br> <img src="docs/goose-js.svg" width="100px" height="60px"/>                                 | 0.01  |                                                                                                                                                                              |
| goose_node <br> <img src="docs/goose-node.svg" width="100px" height="60px"/>                             | 0.01  |                                                                                                                                                                              |
| goose_swift <br> <img src="docs/goose-swift.svg" width="100px" height="60px"/>                           | 0.01  |                                                                                                                                                                              |
| goose_linux <br> <img src="docs/goose-linux.svg" width="100px" height="60px"/>                           | 0.01  |                                                                                                                                                                              |
| goose_spring <br> <img src="docs/goose-spring.svg" width="100px" height="60px"/>                         | 0.01  |                                                                                                                                                                              |
| little_chick <br> <img src="docs/little-chick.svg" width="45px" height="30px"/>                          | 0.9   |                                                                                                                                                                              |
| little_chick_sunfsuglasses <br> <img src="docs/little-chick-sunglasses.svg" width="45px" height="30px"/> | 0.4   |                                                                                                                                                                              |
| little_chick_kotlin <br> <img src="docs/little-chick-kotlin.svg" width="80px" height="30px"/>            | 0.01  |                                                                                                                                                                              |
| little_chick_java <br> <img src="docs/little-chick-java.svg" width="80px" height="30px"/>                | 0.01  |                                                                                                                                                                              |
| little_chick_js <br> <img src="docs/little-chick-js.svg" width="80px" height="30px"/>                    | 0.01  |                                                                                                                                                                              |
| little_chick_node <br> <img src="docs/little-chick-node.svg" width="80px" height="30px"/>                | 0.01  |                                                                                                                                                                              |
| little_chick_swift <br> <img src="docs/little-chick-swift.svg" width="80px" height="30px"/>              | 0.01  |                                                                                                                                                                              |
| little_chick_linux <br> <img src="docs/little-chick-linux.svg" width="80px" height="30px"/>              | 0.01  |                                                                                                                                                                              |
| little_chick_spring <br> <img src="docs/little-chick-spring.svg" width="80px" height="30px"/>            | 0.01  |                                                                                                                                                                              |
| penguin <br> <img src="docs/penguin.svg" width="120px" height="70px"/>                                   | 0.5   |                                                                                                                                                                              |
| penguin_sunglasses <br> <img src="docs/penguin-sunglasses.svg" width="120px" height="70px"/>             | 0.2   |                                                                                                                                                                              |
| penguin_kotlin <br> <img src="docs/penguin-kotlin.svg" width="120px" height="70px"/>                     | 0.01  |                                                                                                                                                                              |
| penguin_java <br> <img src="docs/penguin-java.svg" width="120px" height="70px"/>                         | 0.01  |                                                                                                                                                                              |
| penguin_js <br> <img src="docs/penguin-js.svg" width="120px" height="70px"/>                             | 0.01  |                                                                                                                                                                              |
| penguin_node <br> <img src="docs/penguin-node.svg" width="120px" height="70px"/>                         | 0.01  |                                                                                                                                                                              |
| penguin_swift <br> <img src="docs/penguin-swift.svg" width="120px" height="70px"/>                       | 0.01  |                                                                                                                                                                              |
| penguin_linux <br> <img src="docs/penguin-linux.svg" width="120px" height="70px"/>                       | 0.01  |                                                                                                                                                                              |
| penguin_spring <br> <img src="docs/penguin-spring.svg" width="120px" height="70px"/>                     | 0.01  |                                                                                                                                                                              |
| pig <br> <img src="docs/pig.svg" width="120px" height="90px"/>                                           | 0.2   |                                                                                                                                                                              |
| pig_sunglasses <br> <img src="docs/pig-sunglasses.svg" width="120px" height="90px"/>                     | 0.08  |                                                                                                                                                                              |
| pig_kotlin <br> <img src="docs/pig-kotlin.svg" width="120px" height="90px"/>                             | 0.01  |                                                                                                                                                                              |
| pig_java <br> <img src="docs/pig-java.svg" width="120px" height="90px"/>                                 | 0.01  |                                                                                                                                                                              |
| pig_js <br> <img src="docs/pig-js.svg" width="120px" height="90px"/>                                     | 0.01  |                                                                                                                                                                              |
| pig_node <br> <img src="docs/pig-node.svg" width="120px" height="90px"/>                                 | 0.01  |                                                                                                                                                                              |
| pig_swift <br> <img src="docs/pig-swift.svg" width="120px" height="90px"/>                               | 0.01  |                                                                                                                                                                              |
| pig_linux <br> <img src="docs/pig-linux.svg" width="120px" height="90px"/>                               | 0.01  |                                                                                                                                                                              |
| pig_spring <br> <img src="docs/pig-spring.svg" width="120px" height="90px"/>                             | 0.01  |                                                                                                                                                                              |
| slime_red <br> <img src="docs/slime-red.svg" width="50px" height="40px"/>                                | 0.1   |                                                                                                                                                                              |
| slime_red_kotlin <br> <img src="docs/slime-red-kotlin.svg" width="50px" height="40px"/>                  | 0.001 |                                                                                                                                                                              |
| slime_red_java <br> <img src="docs/slime-red-java.svg" width="50px" height="40px"/>                      | 0.001 |                                                                                                                                                                              |
| slime_red_js <br> <img src="docs/slime-red-js.svg" width="50px" height="40px"/>                          | 0.001 |                                                                                                                                                                              |
| slime_red_node <br> <img src="docs/slime-red-node.svg" width="50px" height="40px"/>                      | 0.001 |                                                                                                                                                                              |
| slime_red_swift <br> <img src="docs/slime-red-swift.svg" width="50px" height="40px"/>                    | 0.001 |                                                                                                                                                                              |
| slime_red_linux <br> <img src="docs/slime-red-linux.svg" width="50px" height="40px"/>                    | 0.001 |                                                                                                                                                                              |
| slime_green <br> <img src="docs/slime-green.svg" width="50px" height="40px"/>                            | 0.1   |                                                                                                                                                                              |
| slime_blue <br> <img src="docs/slime-blue.svg" width="50px" height="40px"/>                              | 0.1   |                                                                                                                                                                              |
| cheese_cat_collaborator <br> <img src="docs/cheese-cat-collaborator.svg" width="100px" height="70px"/>   | 0.0   | Pet made for collaborator [devxb](https://github.com/devxb)                                                                                                                  |
| dessert_fox_collaborator <br> <img src="docs/dessert-fox-collaborator.svg" width="80px" height="65px"/>  | 0.0   | Pet made for collaborator [sumi-001](https://github.com/sumi-0011)                                                                                                           |
| white_cat_collaborator <br> <img src="docs/white-cat-collaborator.svg" width="100px" height="70px"/>     | 0.0   | Pet made for collaborator [Ha youna](https://www.behance.net/hyn991022a6be)                                                                                                  |
| pig_collaborator <br> <img src="docs/pig-collaborator.svg" width="120px" height="90px"/>                 | 0.0   | Pet made for collaborator [hyesungoh](https://github.com/hyesungoh)                                                                                                          |

##

<div align="center">
<p> 아이디어나 발견 한 버그가 있다면 제보 해주세요.
<i>Contact : develxb@gmail.com</i></p>

<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fdevxb%2Fgitanimals&count_bg=%23000000&title_bg=%23000000&icon=&icon_color=%23000000&title=hits&edge_flat=true"/></a>
</div>
