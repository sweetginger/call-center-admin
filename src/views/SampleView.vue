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
                <ul class="submenu">
                  <li>나의 상담</li>
                  <li>전체 상담</li>
                  <li>폭언 관리</li>
                </ul>
              </li>
              <li class="list-item">
                <i class="fas fa-users"></i>운영관리
                <ul class="submenu">
                  <li>운영시간 관리</li>
                  <li>상담원 관리</li>
                </ul>
              </li>
              <li class="list-item">
                <i class="fas fa-chart-bar"></i>통계
                <ul class="submenu">
                  <li>A통계</li>
                  <li>B통계</li>
                  <li>C통계</li>
                  <li>D통계</li>
                </ul>
              </li>
            </ul>
          </div>
        </nav>
        <section id="section1">
          <div class="section">
            <div class="contentTitle">상담 정보</div>
            <div class="callInfo infoBox" style>
              <div
                class="userInfo"
                style="width: 200px; height: 150px; float: left; padding: 0 15px;"
              >
                <div class="title">고객 정보</div>
                <ul class="blackFlag">
                  <li style="width: 50px;">
                    <img src="@/assets/img/icons8-happy-100.png" />
                  </li>
                  <li style="width: 120px;">nobl74</li>
                </ul>
              </div>
              <div
                class="numberInfo"
                style="width: 500px; height: 150px;float: left; padding: 0 15px;"
              >
                <div class="title">
                  수신 정보
                  <ul class="horizon">
                    <li>SMS발송</li>
                    <li>상담이관</li>
                  </ul>
                </div>
                <ul class="horizon" style>
                  <li>
                    <div class="userLevel">일반</div>
                  </li>
                  <li>
                    <span>대표</span>
                  </li>
                  <li>
                    <ul>
                      <li>
                        수신번호 : 02-1234-1234
                        <span class="callBtn">
                          <i class="fas fa-phone-volume"></i>
                        </span>
                      </li>
                      <li>
                        등록번호 : 010-2222-3333
                        <span class="callBtn">
                          <i class="fas fa-phone-volume"></i>
                        </span>
                      </li>
                    </ul>
                  </li>
                </ul>
              </div>
              <div
                class="questionInfo"
                style="width: 400px; height: 150px;float: left; padding: 0 15px;"
              >
                <div class="title">문의 정보</div>
                <ul class="callDepth horizon">
                  <li>해외항공</li>
                  <li>> 결제시한문의</li>
                </ul>
              </div>
            </div>
            <div class="infoBox">
              <table>
                <tr>
                  <th>No.</th>
                  <th>상품유형</th>
                  <th>예약/주문번호</th>
                  <th>예약상태</th>
                  <th>이름</th>
                  <th>구분/이용자</th>
                  <th>상품명</th>
                  <th>목적지/도시</th>
                  <th>출발/이용일</th>
                  <th>도착/종료일</th>
                  <th>담당자</th>
                </tr>
                <tr>
                  <td>1</td>
                  <td>해외항공</td>
                  <td>WBC1HW</td>
                  <td>발권완료</td>
                  <td>오윤배</td>
                  <td>편도</td>
                  <td>국내-제주</td>
                  <td>제주</td>
                  <td>2020.01.01</td>
                  <td>2020.01.05</td>
                  <td>-</td>
                </tr>
                <tr>
                  <td colspan="2">
                    <span style="display: block;">회신약속</span>
                    <i class="fas fa-star" style="color: #ddd;"></i>
                  </td>
                  <td colspan="9" class="callMemo">
                    <div>
                      <select>
                        <option>분류</option>
                      </select>
                      <select>
                        <option>문의유형</option>
                      </select>
                    </div>
                    <div>
                      <!--
                      <input type="checkbox" value="0" />단순안내처리
                      <input type="checkbox" value="1" />아웃콜약속
                      <input type="checkbox" value="2" />상담이관
                      <input type="checkbox" value="3" />무응답종료
                      <input type="checkbox" value="4" />직접입력
                      -->
                      <input type="checkbox" value="0" id="customCheckbox_1" />
                      <label for="customCheckbox_1">단순안내처리</label>
                      <input type="checkbox" value="1" id="customCheckbox_2" />
                      <label for="customCheckbox_2">아웃콜약속</label>
                      <input type="checkbox" value="2" id="customCheckbox_3" />
                      <label for="customCheckbox_3">상담이관</label>
                      <input type="checkbox" value="3" id="customCheckbox_4" />
                      <label for="customCheckbox_4">무응답종료</label>
                      <input type="checkbox" value="4" id="customCheckbox_5" />
                      <label for="customCheckbox_5">직접입력</label>
                    </div>
                    <div class="textMemo">
                      <textarea />
                      <div class="saveBtn">상담저장</div>
                    </div>
                  </td>
                </tr>
              </table>
            </div>
            <div class="infoBox">
              <div class="tabArea">
                <ul>
                  <li :class="{ active: content.tab == 1 }" @click="changeTab('content', 1)">고객정보</li>
                  <li :class="{ active: content.tab == 2 }" @click="changeTab('content', 2)">상담이력</li>
                  <li style="width: 60%; height: 36px;" />
                </ul>
              </div>
              <div class="tab tab1" v-if="content.tab == 1">
                <div class="subTitle">고객정보</div>
                <table>
                  <tr>
                    <th>회원번호</th>
                    <th>ID</th>
                    <th>고객명</th>
                    <th>연락처</th>
                  </tr>
                  <tr>
                    <td>2101296963</td>
                    <td>nobl74</td>
                    <td>오윤배</td>
                    <td>010-1234-1234</td>
                  </tr>
                  <tr>
                    <td>1111296844</td>
                    <td>hehe0000</td>
                    <td>오윤배</td>
                    <td>010-1234-1234</td>
                  </tr>
                </table>

                <div class="subTitle">최근 예약정보</div>
                <table>
                  <tr>
                    <th>No.</th>
                    <th>상품유형</th>
                    <th>예약/주문번호</th>
                    <th>예약상태</th>
                    <th>이름</th>
                    <th>구분/이용자</th>
                    <th>상품명</th>
                    <th>목적지/도시</th>
                    <th>출발/이용일</th>
                    <th>도착/종료일</th>
                    <th>담당자</th>
                  </tr>
                  <tr>
                    <td>1</td>
                    <td>해외항공</td>
                    <td>WBC1HW</td>
                    <td>발권완료</td>
                    <td>오윤배</td>
                    <td>편도</td>
                    <td>국내-제주</td>
                    <td>제주</td>
                    <td>2020.01.01</td>
                    <td>2020.01.05</td>
                    <td>-</td>
                  </tr>
                </table>
              </div>
            </div>
          </div>
        </section>
        <section id="section2">
          <div class="section">
            <div class="title">나의 상담목록</div>
            <div class="tabArea">
              <ul>
                <li :class="{ active: nav.right.tab == 1 }" @click="changeTab('right', 1)">최근 수발신</li>
                <li :class="{ active: nav.right.tab == 2 }" @click="changeTab('right', 2)">콜백</li>
              </ul>
            </div>
            <div class="tab tab1" v-if="nav.right.tab == 1">
              <select>
                <option>전체 (5)</option>
              </select>
              <div class="searchBarArea">
                <input class="userSearch" type="text" placeholder="고객명 전화번호 검색" />
                <i class="fas fa-search"></i>
              </div>
              <ul>
                <li class="row">
                  <ul class="callItem">
                    <li class="star">
                      <i class="fas fa-star" style="color: #ddd;"></i>
                    </li>
                    <li class="direction">수신</li>
                    <li class="callUser">-</li>
                    <li class="callNumber">02-3434-2323</li>
                  </ul>
                </li>
                <li class="row">
                  <ul class="callItem">
                    <li class="star">
                      <i class="fas fa-star" style="color: #FF9800;"></i>
                    </li>
                    <li class="direction">발신</li>
                    <li class="callUser">-</li>
                    <li class="callNumber">02-3434-2323</li>
                  </ul>
                </li>
                <li class="row" v-for="i in 15" :key="i">
                  <ul class="callItem">
                    <li class="star">
                      <i class="fas fa-star" style="color: #ddd;"></i>
                    </li>
                    <li class="direction">수신</li>
                    <li class="callUser">-</li>
                    <li class="callNumber">02-3434-2323</li>
                  </ul>
                </li>
              </ul>
            </div>
            <div class="tab tab2" v-if="nav.right.tab == 2">
              <select>
                <option>전체 (5)</option>
              </select>
              <div class="searchBarArea">
                <input class="userSearch" type="text" placeholder="고객명 전화번호 검색" />
                <i class="fas fa-search"></i>
              </div>
              <ul>
                <li class="row">
                  <ul class="callItem">
                    <li class="star">
                      <i class="fas fa-star" style="color: #ddd;"></i>
                    </li>
                    <li class="direction">1.</li>
                    <li class="callUser">-</li>
                    <li class="callNumber">02-3434-2323</li>
                  </ul>
                </li>
                <li class="row">
                  <ul class="callItem">
                    <li class="star">
                      <i class="fas fa-star" style="color: #FF9800;"></i>
                    </li>
                    <li class="direction">2.</li>
                    <li class="callUser">-</li>
                    <li class="callNumber">02-3434-2323</li>
                  </ul>
                </li>
                <li class="row">
                  <ul class="callItem">
                    <li class="star">
                      <i class="fas fa-star" style="color: #ddd;"></i>
                    </li>
                    <li class="direction">3.</li>
                    <li class="callUser">-</li>
                    <li class="callNumber">02-3434-2323</li>
                  </ul>
                </li>
              </ul>
            </div>
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
export default {
  data: function() {
    return {
      /* right sider 상담목록 탭 전환 변수 */
      nav: {
        right: {
          tab: 1
        }
      },
      content: {
        tab: 1
      }
      /*  */
    };
  },
  methods: {
    /* right sider 상담목록 탭 전환 */
    changeTab: function(areaName, tabNumber) {
      switch (areaName) {
        case "content":
          this.content.tab = tabNumber;
          break;
        case "right":
          this.nav.right.tab = tabNumber;
          break;
      }
    }
  }
};
</script>

<style scoped>
/* @charset "utf-8"; */

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
  font-size: 12px;
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
}

.gnb:after {
  content: "";
  display: block;
  clear: both;
}

/* contents */
section#contents {
  display: flex;
  height: 1000px;
}

section#contents section {
  height: 100%;
}

/* contents - nav */
section#contents nav {
  flex: none;
  width: 200px;
}

#nav {
  height: 100%;
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
.list-item:last-child {
  margin-bottom: 0;
}
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
  width: 1100px;
}

#section1 table {
  width: 96%;
  text-align: center;
  border-collapse: collapse;
  margin: auto;
}

#section1 table th {
  font-size: 16px;
}
#section1 table td {
  font-size: 14px;
  font-weight: 500;
}

#section2 {
  flex: none;
  background-size: cover;
  width: 200px;
  border-left: 1px solid #ddd;
}

/* footer */
footer {
  width: 100%;
  display: table;
}

#footer {
  height: 50px;
  text-align: center;
  line-height: 50px;
  border-top: 1px solid #ddd;
  font-size: 12px;
}
.gnb .callBtnArea {
  width: 380px;
  padding: 20px 0;
  text-align: left;
}
input[type="text"] {
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
}
.callStatusArea .workStatus {
  background: #ddd;
}
.callStatusArea .workStatus li {
  font-size: 12px;
  line-height: 24px;
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
#section2 .tabArea ul {
  height: 35px;
  line-height: 35px;
  margin: 0 2%;
}
#section2 .tabArea ul li {
  float: left;
  width: 50%;
  font-size: 14px;
  border-bottom: 1px solid #bbb;
  color: #bbb;
}
#section2 .tabArea ul li.active {
  border: 1px solid #bbb;
  border-bottom: none;
  color: #000;
}
#section1 .tabArea ul {
  height: 35px;
  line-height: 35px;
  margin: 0 1%;
}
#section1 .tabArea ul li {
  float: left;
  width: 20%;
  font-size: 14px;
  border-bottom: 1px solid #bbb;
  color: #bbb;
  text-align: center;
}
#section1 .tabArea ul li.active {
  border: 1px solid #bbb;
  border-bottom: none;
  color: #000;
}
.tab select {
  width: 93%;
  font-size: 12px;
  height: 30px;
  margin-top: 10px;
}
.infoBox .callMemo select {
  width: 20%;
  font-size: 12px;
  height: 30px;
  margin: 10px 10px 0 0;
}
.tab li.row {
  height: 35px;
  line-height: 35px;
  border-bottom: 1px solid #ddd;
}
.tab li.row:first-child {
  border-top: 1px solid #ddd;
}
.tab .callItem li {
  font-size: 12px;
  float: left;
}
.callItem li.star {
  width: 15%;
}
.callItem li.direction {
  width: 20%;
}
.callItem li.callUser {
  width: 20%;
}
.callItem li.callNumber {
  width: 45%;
}
.tab .searchBarArea {
  margin: 10px 0;
}
.tab .searchBarArea input {
  font-size: 12px;
}
.tab .searchBarArea i {
  margin-left: 5px;
}
select option {
  font-size: 12px;
}
#section2 .title {
  height: 35px;
  line-height: 35px;
  margin: 10px 0;
}
#section1 {
  text-align: left;
}
#section1 table {
  text-align: left;
}
#section1 .contentTitle {
  padding-left: 15px;
  height: 40px;
  line-height: 42px;
  background: #ddd;
  font-weight: 700;
  font-size: 18px;
}

.userInfo .blackFlag {
  width: 180px;
  text-align: center;
  height: 50px;
  line-height: 50px;
}
.userInfo .blackFlag img {
  width: 50px;
}
#section1 .userInfo .blackFlag li {
  float: left;
}
#section1 .title {
  padding: 15px 0;
}
#section1 ul.horizon > li {
  float: left;
  margin-right: 20px;
  height: 35px;
  line-height: 35px;
}
#section1 .title ul.horizon {
  float: right;
}
#section1 .title ul.horizon li {
  line-height: 20px;
}
#section1 .numberInfo .callBtn {
  float: right;
  margin-left: 30px;
}
#section1 .questionInfo ul.horizon > li:last-child {
  float: none;
}
#section1 .questionInfo .callDepth {
  display: block;
}
#section1 .callInfo {
  height: 150px;
}
#section1 .callInfo > div {
  border-left: 1px solid #ddd;
  border-top: 1px solid #ddd;
  border-bottom: 1px solid #ddd;
}
#section1 .callInfo > div:first-child {
  border-left: none;
}
#section1 .infoBox {
  margin-bottom: 10px;
}
#section1 .infoBox table {
  text-align: center;
}
#section1 .infoBox table th:first-child {
  border-left: none;
}
#section1 .infoBox table th {
  border-left: 1px solid #ddd;
}
#section1 .infoBox table tr {
  border-bottom: 1px solid #ddd;
  height: 40px;
  line-height: 40px;
}
#section1 .infoBox table tr:first-child {
  border-top: 1px solid #ddd;
}
#section1 .infoBox .subTitle {
  padding: 30px 0 15px 20px;
  font-weight: 600;
}
.infoBox .callMemo {
  text-align: left;
}
.infoBox .callMemo label {
  margin-right: 20px;
  font-size: 14px;
}
.infoBox .callMemo input[type="checkbox"] {
  width: 14px;
  height: 14px;
  vertical-align: middle;
  margin-right: 5px;
}
.infoBox .callMemo .textMemo {
  height: 90px;
}
.infoBox .callMemo .saveBtn {
  height: 83px;
  width: 100px;
  padding: 20px 0;
  background: #ddd;
  cursor: pointer;
  display: inline-block;
  text-align: center;
  border-radius: 10px;
  margin-left: 5px;
}
.infoBox .callMemo textarea {
  /* height: 83px; */
  width: 88%;
  float: left;
}
.numberInfo .userLevel {
  border: 1px solid #aaa;
  border-radius: 100%;
  display: inline-block;
  padding: 7px 8px;
  margin-top: 10px;
}
/*
input[id^="customCheckbox"] + label {
  display: inline-block;
  width: 20px;
  height: 20px;
  border: 2px solid #bcbcbc;
  cursor: pointer;
}
input[id^="customCheckbox"]:checked + label {
  background-color: #666666;
}
input[id^="customCheckbox"] {
  display: none;
}
*/
</style>
