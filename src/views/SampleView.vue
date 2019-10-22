<template>
  <div class="sampleArea">
    <div id="wrap">
      <div class="btn-top">TOP</div>
      <header>
        <div id="header">
          <div class="gnb">
            <ul>
              <li class="logo">
                <img src="@/assets/logo.png" />
              </li>
              <li class="callBtnArea">
                <input type="text" placeholder="전화번호 입력" />
                <div class="callBtns">
                  <span class="call">
                    <i class="fas fa-phone-volume"></i>
                  </span>
                  <span>
                    <i class="fas fa-volume-mute"></i>
                  </span>
                </div>
              </li>
              <li class="callStatusArea">
                <div>
                  <div class="timer">
                    <span class="statusMsg">상담 대기중</span>
                    <span class="primary">02 : 26 : 54</span>
                  </div>
                  <div class="btns">
                    <!-- <div class="callOn">상담대기</div> -->
                    <ul class="callOn">
                      <li>상담대기</li>
                    </ul>
                    <ul class="workStatus">
                      <li>자리비움</li>
                      <li>작업</li>
                      <li>식사</li>
                    </ul>
                  </div>
                </div>
              </li>
              <li class="callStats">
                <div>
                  <ul>
                    <li>
                      <span>인입</span>
                      <span class="count">203</span>
                    </li>
                    <li>
                      <span>발신</span>
                      <span class="count">9</span>
                    </li>
                  </ul>
                  <ul>
                    <li>
                      <span>콜백</span>
                      <span class="count">2</span>
                    </li>
                    <li>
                      <span>대기</span>
                      <span class="count">11</span>
                    </li>
                  </ul>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </header>
      <section id="contents">
        <nav>
          <div id="nav">
            <div class="title">
              <div class="profile">
                <img src="@/assets/img/icons8-circled-user-64.png" />
                <div class="btns">
                  <i class="fas fa-cog"></i>
                  <i class="fas fa-sign-out-alt"></i>
                </div>
                <div>홍길순 상담원</div>
                <div>
                  <ul class="info">
                    <li class="title">그룹</li>
                    <li>국내여행</li>
                  </ul>
                  <ul class="info">
                    <li class="title">내선</li>
                    <li>6506</li>
                  </ul>
                </div>
              </div>
            </div>
            <ul class="list">
              <li class="list-item">
                <i class="fas fa-phone-alt"></i>상담관리
                <!-- <span class="span">매미</span> -->
              </li>
              <li class="list-item">
                <i class="fas fa-users"></i>운영관리
                <!-- <span class="span">양고기</span> -->
              </li>
              <li class="list-item">
                <i class="fas fa-chart-bar"></i>통계
                <!-- <span class="iamspan">생쥐</span> -->
              </li>
            </ul>
          </div>
        </nav>
        <section id="section1">
          <div class="section">
            <table>
              <colgroup>
                <col width="50px;" />
                <col width="70px;" />
                <col width="70px;" />
                <col width="70px;" />
                <col width="*" />
              </colgroup>
              <legend>시간표</legend>
              <thead>
                <tr>
                  <th>50px</th>
                  <th>70px</th>
                  <th>70px</th>
                  <th>70px</th>
                  <th>나는나머지</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>HTML</td>
                  <td>CSS</td>
                  <td>JS</td>
                  <td>Vue</td>
                  <td>밥먹기</td>
                </tr>
                <tr>
                  <td>HTML</td>
                  <td>CSS</td>
                  <td>JS</td>
                  <td>Vue</td>
                  <td>밥먹기</td>
                </tr>
                <tr>
                  <td>HTML</td>
                  <td>CSS</td>
                  <td>JS</td>
                  <td>Vue</td>
                  <td>밥먹기</td>
                </tr>
                <tr>
                  <td>HTML</td>
                  <td>CSS</td>
                  <td>JS</td>
                  <td>Vue</td>
                  <td>밥먹기</td>
                </tr>
                <tr>
                  <td>HTML</td>
                  <td>CSS</td>
                  <td>JS</td>
                  <td>Vue</td>
                  <td>밥먹기</td>
                </tr>
              </tbody>
            </table>
          </div>
        </section>
        <section id="section2">
          <div class="section">
            <div class="title">나의 상담목록</div>
            <div class="tabArea">
              <ul>
                <li>최근 수발신</li>
                <li>콜백</li>
              </ul>
            </div>
            <div class="tab tab1">
              수발신
              <select>
                <option>전체 (5)</option>
              </select>
              <input type="text" placeholder="고객명 전화번호 검색" />
              <ul>
                <li>
                  <ul class="callItem">
                    <li>
                      <i class="fas fa-star"></i>
                    </li>
                    <li>수신</li>
                    <li>-</li>
                    <li>02-3434-2323</li>
                  </ul>
                </li>
                <li>
                  <ul class="callItem">
                    <li>
                      <i class="fas fa-star"></i>
                    </li>
                    <li>수신</li>
                    <li>-</li>
                    <li>02-3434-2323</li>
                  </ul>
                </li>
                <li>
                  <ul class="callItem">
                    <li>
                      <i class="fas fa-star"></i>
                    </li>
                    <li>수신</li>
                    <li>-</li>
                    <li>02-3434-2323</li>
                  </ul>
                </li>
                <li>
                  <ul class="callItem">
                    <li>
                      <i class="fas fa-star"></i>
                    </li>
                    <li>수신</li>
                    <li>-</li>
                    <li>02-3434-2323</li>
                  </ul>
                </li>
                <li>
                  <ul class="callItem">
                    <li>
                      <i class="fas fa-star"></i>
                    </li>
                    <li>수신</li>
                    <li>-</li>
                    <li>02-3434-2323</li>
                  </ul>
                </li>
              </ul>
            </div>
            <!--
            <div class="tab tab2">
              콜백
              <select>
                <option>전체 (5)</option>
              </select>
              <input type="text" placeholder="고객명 전화번호 검색" />
              <ul>
                <li>
                  <ul class="callItem">
                    <li>
                      <i class="fas fa-star"></i>
                    </li>
                    <li>수신</li>
                    <li>-</li>
                    <li>02-3434-2323</li>
                  </ul>
                </li>
              </ul>
            </div>
            -->
          </div>
        </section>
      </section>
      <footer>
        <div id="footer">Pelly 2019 Hankook Corporation</div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@charset "utf-8";

* {
  margin: 0;
  padding: 0;
  font-size: 16px;
}

ul,
li {
  list-style: none;
}

/*탑버튼*/
.btn-top {
  position: fixed;
  bottom: 80px;
  right: 80px;
  width: 50px;
  height: 50px;
  background-color: #ddd;
  border-radius: 100px;
  line-height: 50px;
}
#wrap {
  width: 1500px;
  margin: auto;
}
/*header*/
header {
  height: 100px;
  border-bottom: 1px solid #ddd;
}

.gnb {
  /* float: right; */
  padding: 10px 0;
  height: 100px;
  box-sizing: border-box;
}
.gnb > ul > li {
  /* width: 400px; */
}
.gnb li {
  float: left;
  margin-right: 30px;
  height: 80px;
  /* line-height: 80px; */
  /* background-color: antiquewhite; */
}

.gnb:after {
  content: "";
  display: block;
  clear: both;
  /*
    가상요소 :before, :after 를 사용한 float 초기화
    요소에 clearfix 라는 클래스를 추가하여 사용하기도 함
    */
}

/* contents */
section#contents {
  display: flex;
  height: 1000px;
}

section#contents section {
  /* flex: 1 1 0; */
  /*
    가장 기본 , flex-grow 증가너비 / flex-shrink 감소너비  / flex-basis 기본너비
    flex-basis 의 기본값은 auto 이지만 단축속성에서 사용할 경우 0 적용
    flex:1; = flex:1 1; = flex:1 1 0;
    가변너비가 아니거나 값이 0일 경우 효과가 없음!
    */
  height: 100%;
}

/* contents - nav */
section#contents nav {
  flex: none;
  width: 200px;
}

#nav {
  height: 100%;
  /* background-color: rgb(150, 149, 149); */
  border-right: 1px solid #ddd;
}

#nav .list {
  margin-top: 100px;
}

.list {
  margin: 30px 0;
  border: 1px solid #ddd;
  border-width: 1px 0;
}

.list-item {
  height: 50px;
  line-height: 50px;
  background-color: #ddd;
  text-align: left;
  padding-left: 15px;
}
.list-item i {
  width: 30px;
  text-align: center;
  margin-right: 10px;
}
/*
.list-item:nth-child(2n) {
  background-color: darkorchid;
}
*/
.list-item:last-child {
  margin-bottom: 0;
}
/*
.list-item:before {
  content: "가상요소";
  display: inline-block;
  font-size: 10px;
}
*/
.list-item span {
  color: white;
}

.list-item span[class="iamspan"] {
  color: blue;
  font-weight: 600;
}

/* contents - section */
div.section {
  width: 100%;
  height: 100%;
}

#section1 {
}

#section1 table {
  width: 100%;
  text-align: center;
  border-collapse: collapse;
  table-layout: fixed;
}

#section1 table th {
  font-size: 16px;
}
#section1 table td {
  font-size: 14px;
  font-weight: 500;
}

#section1 table tr {
  background-color: seagreen;
}

#section1 table td:not(:last-child) {
  background-color: skyblue;
}

#section2 {
  /* background-color: khaki; */
  flex: none;
  /* background: khaki url("/assets/img/dog.jpg") no-repeat center; */
  background-size: cover;
  /* width: 100%; */
  width: 200px;
  border-left: 1px solid #ddd;
}

/* footer */
footer {
  width: 100%;
  display: table;
}

#footer {
  /* 텍스트를 가운데 위치하도록 하기 */
  background-color: lemonchiffon;
  height: 150px;
  text-align: center;
  line-height: 150px;
}
.gnb .callBtnArea {
  width: 380px;
  padding: 20px 0;
  text-align: left;
}
.gnb .callBtnArea input {
  height: 37.78px;
  -webkit-appearance: none;
  border-style: none;
  border: 1px solid #ccc;
  padding: 0 8px;
}
.gnb .callBtnArea .callBtns span {
  padding: 10px;
  background: #ddd;
  border-radius: 5px;
  margin-left: 2px;
}
.gnb .callBtnArea .callBtns span.call {
  padding: 10px 25px;
  background: #23b2ec;
}
.gnb .callStatusArea {
  width: 400px;
}
.gnb .callStatusArea .timer {
  float: left;
}

.callBtnArea .callBtns {
  display: inline-block;
}
.callStatusArea .timer span {
  display: block;
}
.callStatusArea .btns ul {
  padding: 0 5px;
  margin-right: 5px;
}
.callStatusArea .btns .callOn {
  float: left;
  line-height: 79px;
  height: 80px;
  background: #87ceeb;
}
.callStatusArea .btns .callOn li {
  height: 100%;
}
.callStatusArea .btns ul {
  float: left;
  border-radius: 5px;
}
.callStatusArea .btns ul li {
  float: none;
  height: 24px;
  margin: 2px;
  /* background: #ddd; */
}
.callStatusArea .workStatus {
  background: #ddd;
  /* border-radius: 5px; */
}
.callStatusArea .workStatus li {
  font-size: 12px;
  line-height: 24px;
  /* border-top: 1px solid #fff; */
  border-bottom: 1px solid #efefef;
}
.callStatusArea .workStatus li:first-child {
  border-top: none;
}
.callStatusArea .workStatus li:last-child {
  border: none;
}
.logo {
  width: 200px !important;
  margin-right: 0 !important;
  padding: 27px;
}
.logo img {
  width: 135px;
}
.callStats ul li {
  height: 30px;
  width: 85px;
  text-align: left;
}
.profile .btns i {
  width: 50%;
  padding: 15px 25px;
}
.callStatusArea .timer {
  padding: 0 20px;
}
.callStatusArea .timer .statusMsg {
  text-align: left;
  font-size: 13px;
  padding-top: 8px;
}
.callStatusArea .timer .primary {
  padding-top: 10px;
  font-size: 25px;
  font-weight: 600;
}
.callStats {
  padding: 14px 0;
}
.callStats li span {
  padding: 3px 8px;
}
.callStats li span.count {
  background: #87ceeb69;
  border-radius: 20px;
  font-size: 12px;
}
.profile .info li {
  float: left;
  /* padding: 0 15px; */
}
.profile .info .title {
  padding: 0 15px;
}
</style>
