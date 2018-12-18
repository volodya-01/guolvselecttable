<template>
  <div class="hello" style="width:1280px">
    
   
   <Table :border="showBorder" :stripe="showStripe" :show-header="showHeader" :height="fixedHeader ? 250 : ''" :size="tableSize" :data="tableData3" :columns="tableColumns3"></Table>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      tableData3: [
        {
          t: "LXER-52",
          d: 18,
          f: "上海水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 24,
          f: "上海水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 30,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 26,
          f: "合肥水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 18,
          f: "江西水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 24,
          f: "合肥水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 30,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 26,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 18,
          f: "上海水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 24,
          f: "上海水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 30,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 26,
          f: "合肥水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 18,
          f: "江西水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 24,
          f: "合肥水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 30,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 26,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 18,
          f: "上海水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 24,
          f: "上海水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 30,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 26,
          f: "合肥水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 18,
          f: "江西水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 24,
          f: "合肥水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 30,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        },
        {
          t: "LXER-52",
          d: 26,
          f: "北京水表厂",
          min: "0.01",
          max: "2500",
          Q1: "85.02",
          Q2: "79.02",
          Q3: "80.02",
          Q4: "78.02"
        }
      ],
      showBorder: false,
      showStripe: false,
      showHeader: true,
      showIndex: true,
      showCheckbox: true,
      fixedHeader: true,
      tableSize: "default"
    };
  },
  computed: {
    tableColumns3() {
      let columns = [];
      if (this.showCheckbox) {
        columns.push({
          type: "selection",
          width: 80,
          align: "center"
        });
      }
      columns.push({
        title: "厂家",
        key: "f",
        sortable: true,
        width: 120,
        filters: [
          {
            label: "上海水表厂",
            value: "上海水表厂"
          },
          {
            label: "北京水表厂",
            value: "北京水表厂"
          },
          {
            label: "合肥水表厂",
            value: "合肥水表厂"
          },
          {
            label: "江西水表厂",
            value: "江西水表厂"
          }
        ],
        filterMethod(value, row) {
          /* return row.address.indexOf(value) > -1; */
          return row.f === value;
        }
      });

      if (this.showIndex) {
        columns.push({
          title: "序号",
          type: "index",
          width: 80,
          align: "center"
        });
      }

      columns.push({
        title: "表型",
        key: "t",
        width: 140
      });
      columns.push({
        title: "直径",
        key: "d",
        width: 120
        /* sortable: true */
      });
      columns.push({
        title: "最小刻度",
        key: "min",
        sortable: false,
        width: 120
      });
      columns.push({
        title: "量程",
        key: "量程",
        sortable: false,
        width: 120
      });
      columns.push({
        title: "Q1",
        key: "Q1",
        sortable: false,
        width: 120
      });
      columns.push({
        title: "Q2",
        key: "Q2",
        sortable: false,
        width: 120
      });
      columns.push({
        title: "Q3",
        key: "Q3",
        sortable: false,
        width: 120
      });
      columns.push({
        title: "Q4",
        key: "Q4",
        sortable: false,
        width: 120
      });

      return columns;
    }
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
