<template>
  <div class="boxMax">
    <div class="topItem">
      <div class="top"></div>
      <div class="line"></div>
    </div>
    <div class="contentBox" ref="boxContent">
      <div class="fakeBox" id="fakeLine" ref="fake"></div>
      <!-- <div class="userBoxMax">
        <div class="userBox">
          <div class="lineIcon">
            <div class="line"></div>
            <div class="icon">*</div>
            <div class="line"></div>
            <div class="icon">#</div>
            <div class="line"></div>
          </div>
          <div class="box">
            <div class="warp">
              <div class="content">
                <div class="avatar"></div>
                <div class="department">财务部</div>
                <div class="name">路飞</div>
              </div>
              <div class="endBox">
                <span class="operation">编辑</span>
                <span class="operation">新增</span>
                <span class="operation">删除</span>
              </div>
            </div>
          </div>
        </div>
        <div class="userBoxMax child firstChild">
          <div class="childLine"></div>
          <div class="userBox">
            <div class="lineIcon">
              <div class="line"></div>
              <div class="icon">*</div>
              <div class="line"></div>
              <div class="icon">#</div>
              <div class="line"></div>
            </div>
            <div class="box">
              <div class="warp">
                <div class="content">
                  <div class="avatar"></div>
                  <div class="department">财务部</div>
                  <div class="name">路飞</div>
                </div>
                <div class="endBox">
                  <span class="operation">编辑</span>
                  <span class="operation">新增</span>
                  <span class="operation">删除</span>
                </div>
              </div>
            </div>
          </div>
          <div class="userBoxMax child firstChild">
            <div class="childLine"></div>
            <div class="userBox">
              <div class="lineIcon">
                <div class="line"></div>
                <div class="icon">*</div>
                <div class="line"></div>
                <div class="icon">#</div>
                <div class="line"></div>
              </div>
              <div class="box">
                <div class="warp">
                  <div class="content">
                    <div class="avatar"></div>
                    <div class="department">财务部</div>
                    <div class="name">路飞</div>
                  </div>
                  <div class="endBox">
                    <span class="operation">编辑</span>
                    <span class="operation">新增</span>
                    <span class="operation">删除</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="userBoxMax child child-child">
            <div class="childLine"></div>
            <div class="userBox">
              <div class="lineIcon">
                <div class="line"></div>
                <div class="icon">*</div>
                <div class="line"></div>
                <div class="icon">#</div>
                <div class="line"></div>
              </div>
              <div class="box">
                <div class="warp">
                  <div class="content">
                    <div class="avatar"></div>
                    <div class="department">财务部</div>
                    <div class="name">路飞</div>
                  </div>
                  <div class="endBox">
                    <span class="operation">编辑</span>
                    <span class="operation">新增</span>
                    <span class="operation">删除</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="userBoxMax child">
          <div class="childLine" :style="ChildLine"></div>
          <div class="userBox">
            <div class="lineIcon">
              <div class="line"></div>
              <div class="icon">*</div>
              <div class="line"></div>
              <div class="icon">#</div>
              <div class="line"></div>
            </div>
            <div class="box">
              <div class="warp">
                <div class="content">
                  <div class="avatar"></div>
                  <div class="department">财务部</div>
                  <div class="name">路飞</div>
                </div>
                <div class="endBox">
                  <span class="operation">编辑</span>
                  <span class="operation">新增</span>
                  <span class="operation">删除</span>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="userBoxMax child">
          <div class="childLine"></div>
          <div class="userBox">
            <div class="lineIcon">
              <div class="line"></div>
              <div class="icon">*</div>
              <div class="line"></div>
              <div class="icon">#</div>
              <div class="line"></div>
            </div>
            <div class="box">
              <div class="warp">
                <div class="content">
                  <div class="avatar"></div>
                  <div class="department">财务部</div>
                  <div class="name">路飞</div>
                </div>
                <div class="endBox">
                  <span class="operation">编辑</span>
                  <span class="operation">新增</span>
                  <span class="operation">删除</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="userBoxMax">
        <div class="userBox">
          <div class="lineIcon">
            <div class="line"></div>
            <div class="icon">*</div>
            <div class="line"></div>
            <div class="icon">#</div>
            <div class="line"></div>
          </div>
          <div class="box">
            <div class="warp">
              <div class="content">
                <div class="avatar"></div>
                <div class="department">财务部</div>
                <div class="name">路飞</div>
              </div>
              <div class="endBox">
                <span class="operation">编辑</span>
                <span class="operation">新增</span>
                <span class="operation">删除</span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="userBoxMax">
        <div class="userBox">
          <div class="lineIcon">
            <div class="line"></div>
            <div class="icon">*</div>
            <div class="line"></div>
            <div class="icon">#</div>
            <div class="line"></div>
          </div>
          <div class="box">
            <div class="warp">
              <div class="content">
                <div class="avatar"></div>
                <div class="department">财务部</div>
                <div class="name">路飞</div>
              </div>
              <div class="endBox">
                <span class="operation">编辑</span>
                <span class="operation">新增</span>
                <span class="operation">删除</span>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="userBoxMax">
        <div class="userBox">
          <div class="lineIcon">
            <div class="line"></div>
            <div class="icon">*</div>
            <div class="line"></div>
            <div class="icon">#</div>
            <div class="line"></div>
          </div>
          <div class="box">
            <div class="warp">
              <div class="content">
                <div class="avatar"></div>
                <div class="department">财务部</div>
                <div class="name">路飞</div>
              </div>
              <div class="endBox">
                <span class="operation">编辑</span>
                <span class="operation">新增</span>
                <span class="operation">删除</span>
              </div>
            </div>
          </div>
        </div>
      </div> -->
      <div
        v-for="item in treeData.child ? treeData.child : []"
        :key="item.id"
        class="userBoxMax"
      >
        <div class="userBox">
          <div class="lineIcon">
            <div class="line"></div>
            <div class="icon">*</div>
            <div class="line"></div>
            <div class="icon">#</div>
            <div class="line"></div>
          </div>
          <div class="box">
            <div class="warp">
              <div class="content">
                <div class="avatar"></div>
                <div class="department">{{ item.name }}</div>
                <div class="name">{{ item.managerNames }}</div>
              </div>
              <div class="endBox">
                <span class="operation">编辑</span>
                <span class="operation">新增</span>
                <span class="operation">删除</span>
              </div>
            </div>
          </div>
        </div>
        <div
          class="userBoxMax child"
          :class="{ firstChild: idx === 0 }"
          :key="itemSub.id"
          v-for="(itemSub, idx) in item.child ? item.child : []"
        >
          <div
            class="childLine"
            :style="ChildLineSet(item.child[idx - 1])"
          ></div>
          <div class="userBox">
            <div class="lineIcon">
              <div class="line"></div>
              <div class="icon">*</div>
              <div class="line"></div>
              <div class="icon">#</div>
              <div class="line"></div>
            </div>
            <div class="box">
              <div class="warp">
                <div class="content">
                  <div class="avatar"></div>
                  <div class="department">{{ itemSub.name }}</div>
                  <div class="name">{{ itemSub.managerNames }}</div>
                </div>
                <div class="endBox">
                  <span class="operation">编辑</span>
                  <span class="operation">新增</span>
                  <span class="operation">删除</span>
                </div>
              </div>
            </div>
          </div>
          <div
            class="userBoxMax child"
            :class="{ firstChild: i === 0 }"
            :key="itemSubSub.id"
            v-for="(itemSubSub, i) in itemSub.child ? itemSub.child : []"
          >
            <div
              class="childLine"
              :style="ChildLineSet(itemSub.child[i - 1])"
            ></div>
            <div class="userBox">
              <div class="lineIcon">
                <div class="line"></div>
                <div class="icon">*</div>
                <div class="line"></div>
                <div class="icon">#</div>
                <div class="line"></div>
              </div>
              <div class="box">
                <div class="warp">
                  <div class="content">
                    <div class="avatar"></div>
                    <div class="department">{{ itemSubSub.name }}</div>
                    <div class="name">{{ itemSubSub.managerNames }}</div>
                  </div>
                  <div class="endBox">
                    <span class="operation">编辑</span>
                    <span class="operation">新增</span>
                    <span class="operation">删除</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    const data = [
      {
        id: "1",
        name: "宁波海大物联科技有限公司",
        level: 1,
        sequence: 1,
        state: "Y",
        pid: "",
        creator: "7ecc7806c8e14231b4f5323d965ccdc2",
        createTime: 1681889708000,
        updateTime: null,
        source: "ding",
        managerIds: null,
        managerNames: null,
        code: null,
        accountNum: 82,
        deptArr: null,
        child: [
          {
            id: "841731324",
            name: "总经办",
            level: 2,
            sequence: 1,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681889708000,
            updateTime: null,
            source: "ding",
            managerIds: null,
            managerNames: "曹南",
            code: null,
            accountNum: 9,
            deptArr: null,
            child: null,
            accountList: null,
            stateName: "启用",
          },
          {
            id: "846067786",
            name: "财务部",
            level: 2,
            sequence: 2,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681889708000,
            updateTime: null,
            source: "ding",
            managerIds: null,
            managerNames: "朱艳",
            code: null,
            accountNum: 1,
            deptArr: null,
            child: null,
            accountList: null,
            stateName: "启用",
          },
          {
            id: "846314013",
            name: "销售部",
            level: 2,
            sequence: 3,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681889708000,
            updateTime: null,
            source: "ding",
            managerIds: null,
            managerNames: "屈琪辉",
            code: null,
            accountNum: 9,
            deptArr: null,
            child: null,
            accountList: null,
            stateName: "启用",
          },
          {
            id: "846326658",
            name: "深圳",
            level: 2,
            sequence: 4,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681889708000,
            updateTime: null,
            source: "ding",
            managerIds: null,
            managerNames: null,
            code: null,
            accountNum: 1,
            deptArr: null,
            child: null,
            accountList: null,
            stateName: "启用",
          },
          {
            id: "844596327",
            name: "技术部",
            level: 2,
            sequence: 5,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681889708000,
            updateTime: null,
            source: "ding",
            managerIds: null,
            managerNames: null,
            code: null,
            accountNum: 62,
            deptArr: null,
            child: [
              {
                id: "844827015",
                name: "硬件部",
                level: 3,
                sequence: 1,
                state: "Y",
                pid: "844596327",
                creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                createTime: 1681889708000,
                updateTime: null,
                source: "ding",
                managerIds: null,
                managerNames: "郁存",
                code: null,
                accountNum: 12,
                deptArr: null,
                child: null,
                accountList: null,
                stateName: "启用",
              },
              {
                id: "846044882",
                name: "运营中心",
                level: 3,
                sequence: 1,
                state: "Y",
                pid: "844596327",
                creator: null,
                createTime: 1681980747000,
                updateTime: null,
                source: "ding",
                managerIds: null,
                managerNames: null,
                code: null,
                accountNum: 7,
                deptArr: null,
                child: [
                  {
                    id: "846279102",
                    name: "运维部",
                    level: 4,
                    sequence: 1,
                    state: "Y",
                    pid: "846044882",
                    creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                    createTime: 1681889708000,
                    updateTime: null,
                    source: "ding",
                    managerIds: null,
                    managerNames: "余晓燕",
                    code: null,
                    accountNum: 3,
                    deptArr: null,
                    child: null,
                    accountList: null,
                    stateName: "启用",
                  },
                  {
                    id: "846322032",
                    name: "UED设计部",
                    level: 4,
                    sequence: 2,
                    state: "Y",
                    pid: "846044882",
                    creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                    createTime: 1681889708000,
                    updateTime: null,
                    source: "ding",
                    managerIds: null,
                    managerNames: "余晓燕",
                    code: null,
                    accountNum: 5,
                    deptArr: null,
                    child: null,
                    accountList: null,
                    stateName: "启用",
                  },
                ],
                accountList: null,
                stateName: "启用",
              },
              {
                id: "846171412",
                name: "项目中心",
                level: 3,
                sequence: 2,
                state: "Y",
                pid: "844596327",
                creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                createTime: 1681889708000,
                updateTime: null,
                source: "ding",
                managerIds: null,
                managerNames: null,
                code: null,
                accountNum: 23,
                deptArr: null,
                child: [
                  {
                    id: "846146449",
                    name: "南京研发部",
                    level: 4,
                    sequence: 1,
                    state: "Y",
                    pid: "846171412",
                    creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                    createTime: 1681889708000,
                    updateTime: null,
                    source: "ding",
                    managerIds: null,
                    managerNames: "周加俊",
                    code: null,
                    accountNum: 4,
                    deptArr: null,
                    child: null,
                    accountList: null,
                    stateName: "启用",
                  },
                  {
                    id: "846322034",
                    name: "项目二部",
                    level: 4,
                    sequence: 2,
                    state: "Y",
                    pid: "846171412",
                    creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                    createTime: 1681889708000,
                    updateTime: null,
                    source: "ding",
                    managerIds: null,
                    managerNames: "王凯乐",
                    code: null,
                    accountNum: 7,
                    deptArr: null,
                    child: null,
                    accountList: null,
                    stateName: "启用",
                  },
                  {
                    id: "846008870",
                    name: "项目三部",
                    level: 4,
                    sequence: 3,
                    state: "Y",
                    pid: "846171412",
                    creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                    createTime: 1681889708000,
                    updateTime: null,
                    source: "ding",
                    managerIds: null,
                    managerNames: null,
                    code: null,
                    accountNum: 6,
                    deptArr: null,
                    child: null,
                    accountList: null,
                    stateName: "启用",
                  },
                  {
                    id: "846022973",
                    name: "项目一部",
                    level: 4,
                    sequence: 4,
                    state: "Y",
                    pid: "846171412",
                    creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                    createTime: 1681889708000,
                    updateTime: null,
                    source: "ding",
                    managerIds: null,
                    managerNames: "徐龙",
                    code: null,
                    accountNum: 6,
                    deptArr: null,
                    child: null,
                    accountList: null,
                    stateName: "启用",
                  },
                ],
                accountList: null,
                stateName: "启用",
              },
              {
                id: "844719147",
                name: "冷链事业部",
                level: 3,
                sequence: 4,
                state: "Y",
                pid: "844596327",
                creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                createTime: 1681889708000,
                updateTime: null,
                source: "ding",
                managerIds: null,
                managerNames: "李振,陈开宇",
                code: null,
                accountNum: 15,
                deptArr: null,
                child: null,
                accountList: null,
                stateName: "启用",
              },
              {
                id: "846183347",
                name: "基础研发部",
                level: 3,
                sequence: 5,
                state: "Y",
                pid: "844596327",
                creator: "7ecc7806c8e14231b4f5323d965ccdc2",
                createTime: 1681889708000,
                updateTime: null,
                source: "ding",
                managerIds: null,
                managerNames: "温小斌",
                code: null,
                accountNum: 5,
                deptArr: null,
                child: null,
                accountList: null,
                stateName: "启用",
              },
            ],
            accountList: null,
            stateName: "启用",
          },
          {
            id: "846026897",
            name: "青岛",
            level: 2,
            sequence: 6,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681889708000,
            updateTime: null,
            source: "ding",
            managerIds: null,
            managerNames: null,
            code: null,
            accountNum: 1,
            deptArr: null,
            child: null,
            accountList: null,
            stateName: "启用",
          },
          {
            id: "5b67540c5d1d48f9b71c88b0a6221cd7",
            name: "测试服测试",
            level: 2,
            sequence: 7,
            state: "Y",
            pid: "1",
            creator: "7ecc7806c8e14231b4f5323d965ccdc2",
            createTime: 1681893146650,
            updateTime: null,
            source: "zeus",
            managerIds: null,
            managerNames: null,
            code: null,
            accountNum: 0,
            deptArr: null,
            child: null,
            accountList: null,
            stateName: "启用",
          },
        ],
        accountList: null,
        stateName: "启用",
      },
    ];
    return {
      initHeight: 65,
      treeData: data[0],
    };
  },
  computed: {
    // ChildLine() {
    //   return {
    //     height: this.initHeight + this.minChildLineNum * 65 + "px",
    //     top: -34 - this.minChildLineNum * 65 + "px",
    //   };
    // },
  },
  methods: {
    ChildLineSet(sibling) {
      let num = 0;
      if (sibling && sibling.child && sibling.child.length) {
        num = sibling.child.length;
      }
      return {
        height: this.initHeight + num * 65 + "px",
        top: -32 - num * 65 + "px",
      };
    },

    setLineFake() {
      this.$refs.fake.style.height =
        this.$refs.boxContent.clientHeight - 64 + "px";
    },
  },
  mounted() {
    this.setLineFake();
  },
};
</script>
<style lang="less" scoped>
.boxMax {
  width: 1200px;
  height: 1400px;
  border: 1px solid black;
  padding: 24px;
  display: flex;
  align-items: center;
  background-image: url("../assets/bg.png");
  background-repeat: no-repeat;
  background-size: cover;
  .topItem {
    display: flex;
    align-items: center;
    .top {
      width: 80px;
      height: 80px;
      background-color: red;
    }
    .line {
      width: 16px;
      height: 1px;
      background-color: #e4e7ed;
    }
  }
  .contentBox {
    width: 900px;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    position: relative;
    .fakeBox {
      position: absolute;
      width: 1px;
      background-color: #e4e7ed;
      align-items: start;
    }
    .userBoxMax {
      display: flex;
      flex-direction: column;
    }
    .userBox {
      margin: 8px 0;
      display: flex;
      align-items: center;
      .lineIcon {
        display: flex;
        align-items: center;
        width: 104px;
        .line {
          width: 16px;
          height: 1px;
          background-color: #e4e7ed;
        }
        .icon {
          display: flex;
          justify-content: center;
          align-items: center;
          width: 32px;
          height: 32px;
          background: #ffffff;
          border: 1px solid #dcdfe6;
        }
      }
      .box {
        display: flex;
        flex-direction: column;
        flex: 1;
      }
      .warp {
        display: flex;
        align-items: center;
        justify-content: space-between;
        background: linear-gradient(
          90deg,
          rgba(64, 158, 255, 0.1) 0%,
          rgba(64, 158, 255, 0) 100%
        );
        border-radius: 4px;
        border: 1px solid;
        border-image: linear-gradient(
            90deg,
            rgba(64, 158, 255, 0.2),
            rgba(64, 158, 255, 0.1)
          )
          1 1;
        .content {
          height: 48px;
          position: relative;
          padding-left: 56px;
          display: flex;
          align-items: center;
          .avatar {
            background-image: url("../assets/avatar.png");
            background-repeat: no-repeat;
            background-size: cover;
            width: 56px;
            height: 56px;
            position: absolute;
            bottom: 0;
            left: 0;
          }
          .department {
            font-size: 14px;
            font-weight: 600;
            color: #303133;
            margin-left: 24px;
          }
          .name {
            font-size: 14px;
            color: #606265;
            margin-left: 24px;
          }
        }
        .endBox {
          background-image: url("../assets/end.png");
          background-repeat: no-repeat;
          background-size: cover;
          display: flex;
          justify-content: end;
          align-items: center;
          .operation {
            width: 28px;
            height: 22px;
            cursor: pointer;
            font-size: 14px;
            font-weight: 600;
            color: #409eff;
            line-height: 22px;
            padding: 0 16px;
          }
        }
      }
    }
    // .up {
    //   transform: translateY(-36px);
    // }
    // .down {
    //   transform: translateY(36px);
    // }
  }
}
.child {
  padding-left: 128px;
  position: relative;
  .childLine {
    position: absolute;
    width: 1px;
    height: 65px;
    top: -34px;
    background-color: #e4e7ed;
  }
}
.firstChild {
  .childLine {
    position: absolute;
    width: 1px;
    height: 42px !important;
    top: -8px !important;
    background-color: #e4e7ed;
  }
}
.child-child {
  .childLine {
    position: absolute;
    width: 1px;
    height: 65px;
    top: -25px;
    background-color: #e4e7ed;
  }
}
</style>
