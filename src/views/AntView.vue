<template>
  <div class="templateView">
    <a-layout id="components-layout-demo-fixed">
      <a-layout-header
        :style="{
          position: 'fixed',
          zIndex: 1,
          width: '100%',
          background: '#fff',
          display: 'flex'
        }"
      >
        <div class="logo" style="margin-right: 49px">
          <img
            style="width: 100px"
            src="https://sslimage.interpark.com/.ui/interparkMain/2017/common/header/logo_interparkS.png"
          />
        </div>
        <!--
        <a-menu
          theme="light"
          mode="horizontal"
          :defaultSelectedKeys="['1']"
          :style="{ lineHeight: '64px' }"
        >
        -->
        <!-- <a-input placeholder="default size" stype="width: 200px" /> -->
        <a-row type="flex" justify="end">
          <a-col :span="20">
            <a-input
              :value="value"
              @change="onChange"
              @blur="onBlur"
              placeholder="전화번호 입력"
              :maxLength="25"
              style="width: 200px"
            />
            <a-button-group>
              <a-button type="primary" icon="phone" />
              <a-button icon="sound" />
            </a-button-group>
          </a-col>
          <!--
          <a-menu-item key="1">nav 1</a-menu-item>
          <a-menu-item key="2">nav 2</a-menu-item>
          <a-menu-item key="3">nav 3</a-menu-item>
          <div style="border: 1px solid #ddd;">
            <span>통화대기중</span>
            00 : 02 : 26
          </div>
          <a-statistic
            title="통화대기중"
            :value="22826"
            
          />
          -->
          <a-col :span="2">colcolcolcolcolcol</a-col>
          <a-col :span="2">colcolcolcolcolcol</a-col>
        </a-row>
        <!-- </a-menu> -->
      </a-layout-header>
      <!--
      <a-layout-content :style="{ padding: '0 50px', marginTop: '64px' }">
        <a-breadcrumb :style="{ margin: '16px 0' }">
          <a-breadcrumb-item>Home</a-breadcrumb-item>
          <a-breadcrumb-item>List</a-breadcrumb-item>
          <a-breadcrumb-item>App</a-breadcrumb-item>
        </a-breadcrumb>
        <div :style="{ background: '#fff', padding: '24px', minHeight: '380px' }">Content</div>
      </a-layout-content>
      <a-layout-footer :style="{ textAlign: 'center' }">Ant Design ©2018 Created by Ant UED</a-layout-footer>
    </a-layout>
      -->
      <a-layout id="components-layout-demo-fixed-sider">
        <a-layout-sider
          :style="{
            overflow: 'auto',
            height: '100vh',
            position: 'fixed',
            left: 0,
            background: '#fff'
          }"
        >
          <div class="logo"></div>
          <a-menu
            theme="light"
            mode="inline"
            :defaultSelectedKeys="['1']"
            :defaultOpenKeys="['sub1', 'sub2', 'sub3']"
            :style="{ float: 'left' }"
          >
            <!--
            <a-card size="small" title="홍길순 과장" style="width: 180px; margin: 0 10px;">
              <a href="#" slot="extra">
                <a-icon type="setting" theme="filled" />
              </a>
              <p>그룹 - 국내숙박</p>
              <p>내선 - 6516</p>
            </a-card>
            -->
            <a-card hoverable style="width: 180px; margin: 0 10px;">
              <template class="ant-card-actions" slot="actions">
                <!--
                <a-icon type="setting" />
                <a-icon type="edit" />
                <a-icon type="ellipsis" />
                -->
                <a style="font-size: 11px;">자리비움</a>
                <a style="font-size: 11px;">작업</a>
                <a style="font-size: 11px;">식사</a>
              </template>
              <a-card-meta title="홍길순" description="국내숙박 6516">
                <!--
                <a-avatar
                  slot="avatar"
                  src="https://zos.alipayobjects.com/rmsportal/ODTLcjxAfvqbxHnVXCYX.png"
                />
                -->
                <a-avatar slot="avatar" size="large" icon="user" />
              </a-card-meta>
            </a-card>
            <a-sub-menu key="sub1">
              <span slot="title">
                <a-icon type="user" />
                <span>상담 관리</span>
              </span>
              <a-menu-item key="1">나의 상담</a-menu-item>
              <a-menu-item key="2">전체 상담</a-menu-item>
              <a-menu-item key="3">폭언 관리</a-menu-item>
            </a-sub-menu>
            <a-sub-menu key="sub2">
              <span slot="title">
                <a-icon type="video-camera" />
                <span>운영 관리</span>
              </span>
              <a-menu-item key="4">운영시간 관리</a-menu-item>
              <a-menu-item key="5">상담원 관리</a-menu-item>
            </a-sub-menu>
            <a-sub-menu key="sub3">
              <span slot="title">
                <a-icon type="video-camera" />
                <span>통계</span>
              </span>
              <a-menu-item key="6">통계항목1</a-menu-item>
              <a-menu-item key="7">통계항목2</a-menu-item>
              <a-menu-item key="8">통계항목3</a-menu-item>
              <a-menu-item key="9">통계항목4</a-menu-item>
            </a-sub-menu>
          </a-menu>
        </a-layout-sider>
        <a-layout :style="{ margin: '0 200px' }">
          <a-layout-header :style="{ background: '#fff', padding: 0 }" />
          <a-layout-content
            :style="{ margin: '24px 16px 0', overflow: 'initial' }"
          >
            <div
              :style="{
                padding: '24px',
                background: '#fff',
                height: '100vh'
              }"
            >
              컨텐츠영역
              <div>
                <a-row>
                  <a-col :span="6" :pull="18">
                    <span style>고객 정보</span>
                    <span>nobl74</span>
                  </a-col>
                  <a-col :span="18" :push="6"></a-col>
                </a-row>
              </div>
              <div>
                <a-row>
                  <a-col :span="6" :pull="18">col-6 col-pull-18</a-col>
                  <a-col :span="18" :push="6">col-18 col-push-6</a-col>
                </a-row>
              </div>
              <div>
                <a-row>
                  <a-col :span="6" :pull="18">col-6 col-pull-18</a-col>
                  <a-col :span="18" :push="6">col-18 col-push-6</a-col>
                </a-row>
              </div>
              <div>
                <a-row>
                  <a-col :span="6" :pull="18">col-6 col-pull-18</a-col>
                  <a-col :span="18" :push="6">col-18 col-push-6</a-col>
                </a-row>
              </div>
            </div>
          </a-layout-content>
          <a-layout-footer
            :style="{
              textAlign: 'center',
              position: 'fixed',
              bottom: 0,
              width: '100%',
              padding: '12px 450px 12px 50px',
              color: '#aaa'
            }"
            >Pelly ©2019 Hankook Corporation</a-layout-footer
          >
          <!--
        </a-layout>
          -->
        </a-layout>
        <!-- <a-layout id="components-layout-demo-fixed-sider"> -->
        <a-layout-sider
          :style="{
            overflow: 'auto',
            height: '100vh',
            position: 'fixed',
            right: 0,
            background: '#fff',
            width: '300px'
          }"
        >
          <div class="logo"></div>
          <!--
          <a-menu theme="light" mode="inline" :defaultSelectedKeys="['4']">
            <a-menu-item key="1">
              <a-icon type="user" />
              <span class="nav-text">nav 1</span>
            </a-menu-item>
            <a-menu-item key="2">
              <a-icon type="video-camera" />
              <span class="nav-text">nav 2</span>
            </a-menu-item>
            <a-menu-item key="3">
              <a-icon type="upload" />
              <span class="nav-text">nav 3</span>
            </a-menu-item>
            <a-menu-item key="4">
              <a-icon type="bar-chart" />
              <span class="nav-text">nav 4</span>
            </a-menu-item>
            <a-menu-item key="5">
              <a-icon type="cloud-o" />
              <span class="nav-text">nav 5</span>
            </a-menu-item>
            <a-menu-item key="6">
              <a-icon type="appstore-o" />
              <span class="nav-text">nav 6</span>
            </a-menu-item>
            <a-menu-item key="7">
              <a-icon type="team" />
              <span class="nav-text">nav 7</span>
            </a-menu-item>
            <a-menu-item key="8">
              <a-icon type="shop" />
              <span class="nav-text">nav 8</span>
            </a-menu-item>
          </a-menu>
          -->
          <a-tabs defaultActiveKey="1">
            <a-tab-pane tab="콜백" key="1">
              <a-table
                :dataSource="callBackListData"
                :pagination="false"
                :scroll-y="true"
              >
                <a-table-column data-index="type" />
                <a-table-column data-index="userId" />
                <a-table-column data-index="phone" />
              </a-table>
            </a-tab-pane>
            <a-tab-pane tab="수발신목록" key="2">
              <a-table :dataSource="callListData" :pagination="false">
                <a-table-column data-index="status" />
                <a-table-column data-index="userId" />
                <a-table-column data-index="phone" />
              </a-table>
            </a-tab-pane>
          </a-tabs>
        </a-layout-sider>
        <!--
          <a-layout :style="{ marginLeft: '200px' }">
            <a-layout-header :style="{ background: '#fff', padding: 0 }" />
            <a-layout-footer :style="{ textAlign: 'center' }">Ant Design ©2018000 Created by Ant UED</a-layout-footer>
          </a-layout>
        </a-layout>
        -->
      </a-layout>
    </a-layout>
  </div>
</template>

<script>
import Vue from "vue";
import Antd from "ant-design-vue";
import "ant-design-vue/dist/antd.css";
Vue.use(Antd);
export default {
  data: function() {
    return {
      /* 통화 시간 카운트 */
      callTime: 0,
      callListData: [
        {
          key: "1",
          status: "수신",
          userId: "",
          phone: "0234742294"
        },
        {
          key: "2",
          status: "발신",
          userId: "",
          phone: "01091918282"
        },
        {
          key: "3",
          status: "발신",
          userId: "",
          phone: "01088375462"
        },
        {
          key: "4",
          status: "수신",
          userId: "",
          phone: "0312253535"
        }
      ],
      callBackListData: [
        {
          key: "1",
          type: "개인정보문의",
          userId: "",
          phone: "0234742294"
        },
        {
          key: "2",
          type: "결제문의",
          userId: "",
          phone: "01091918282"
        },
        {
          key: "3",
          type: "항공문의",
          userId: "",
          phone: "01088375462"
        }
      ]
    };
  }
};
</script>

<style scoped>
#components-layout-demo-fixed-sider .logo {
  height: 32px;
  background: rgba(255, 255, 255, 0.2);
  margin: 16px;
}
</style>
