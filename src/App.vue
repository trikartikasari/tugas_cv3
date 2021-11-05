<template>
<div class="z" >
    <h1 style="text-align: center; background-color: pink; font-family: monopasce;"><i>PROJECT CV</i></h1>
  <div id="app" class="container">
    <div class="ai">
    <div class="row" style="border: 100px solid grey;">
        <div class="a" style="background:darkgrey;">
            <h1 v-for="status in listData" :key="status" style="color:orange;">{{ status.judul }}</h1>
            <img src="https://www.kanalmu.com/ezoimgfmt/1.bp.blogspot.com/-9gnGRBguiDM/XkCluVx9XsI/AAAAAAAAANs/SF9_WhPOBzkyGF39bXjFcrn_rcehrNPCwCLcBGAsYHQ/s640/Gambar%2BKartun%2BMuslimah%2Bkanalmu.com%2B16.jpeg?ezimgfmt=rs:382x417/rscb2/ng:webp/ngcb2" width="auto" height="auto"><br><br>
            <h3 v-for="status in listData" :key="status">{{ status.judul1 }}</h3><hr><br><br>
            <p v-for="status in listData" :key="status"><span ><b>{{ status.alamat }}</b></span><br>
              {{ status.alamat2 }}<br>
            </p>
            <p v-for="status in listData" :key="status"><span><b>{{ status.phone }}</b></span><br>{{ status.phone2 }}</p>
            <p v-for="status in listData" :key="status"><span><b>{{ status.email }}</b></span><br>{{ status.email2 }}</p><br><br><br>
            <h3 v-for="status in listData" :key="status">{{ status.t }}</h3><hr><br>
            <h4 v-for="status in listData" :key="status">{{ status.j }}</h4>
            <h4 v-for="status in listData" :key="status">{{ status.k }}</h4>
            <h4 v-for="status in listData" :key="status">{{ status.l }}</h4>
            <br>
            <br>
            <h3 v-for="status in listData" :key="status">{{ status.u }}</h3><hr><br>
            <ul>
                <li v-for="status in listData" :key="status">{{ status.hobi }}</li>
                <li v-for="status in listData" :key="status">{{ status.hobi1 }}</li>
                <li v-for="status in listData" :key="status">{{ status.hobi2 }}</li>
            </ul>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
        </div>
        <div class="a" style="bakcground-color: white; border: 6px solid white; margin-left: 30px">
            <h3 v-for="status in listData" :key="status">{{ status.v }}</h3><hr>
            <p v-for="status in listData" :key="status">{{ status.objek }}
            </p><br><br>
            <h3 v-for="status in listData" :key="status">{{ status.w }}</h3><hr>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<sub v-for="status in listData" :key="status">{{ status.x }}</sub>
            <p v-for="status in listData" :key="status">{{ status.hidup }}<br>
                <ul>
                    <li v-for="status in listData" :key="status">{{ status.a }}</li>
                    <li v-for="status in listData" :key="status">{{ status.b }}</li>
                    <li v-for="status in listData" :key="status">{{ status.c }}</li>
                    <li v-for="status in listData" :key="status">{{ status.d }}</li>
                    <li v-for="status in listData" :key="status">{{ status.e }}</li>
                    <li v-for="status in listData" :key="status">{{ status.f }}</li>
                    <li v-for="status in listData" :key="status">{{ status.g }}</li>

                </ul></p><br><br>
            <h3 v-for="status in listData" :key="status">{{ status.y }}</h3><hr>
            <p v-for="status in listData" :key="status">{{ status.education }}</p><br><br>
            <h3 v-for="status in listData" :key="status">{{ status.m }}</h3> <hr>
            <p v-for="status in listData" :key="status">{{ status.abiliti }}</p><br><br>
            <h3 v-for="status in listData" :key="status">{{ status.n }}</h3><hr>
            <p v-for="status in listData" :key="status">{{ status.pesan }}</p><br><br>
        </div>
        </div>
    </div><br><br><br>
    <div class="row py-4" >
<div class="row" style="border: 100px solid olive; font-family: sans-serif ">
  <header>
  <legend v-for="status in listData" :key="status" style="background-color:darkkhaki;text-align:center;font-size: 80px; display:flex;border:10px solid darkkhaki"><img src="https://i.pinimg.com/originals/a1/b8/ef/a1b8ef1ce80033bd1afd125c3e2cd9a4.jpg" width=200px height=200px style="border-radius:150px;border-left: 300px; display:flex">{{ status.nama }}</legend>
  </header>
<div class="a" style="text-align:right">
<h3 v-for="status in listData" :key="status" >{{ status.ab }}</h3><hr style="border-top: dashed 1px;" />
 <p v-for="status in listData" :key="status"><span><b>{{ status.ab2 }}</b></span><br>{{ status.ab7 }}</p><br>
 <p v-for="status in listData" :key="status"><span><b>{{ status.ab3 }}</b></span><br>{{ status.ab8 }}</p><br>
 <p v-for="status in listData" :key="status"><span><b>{{ status.ab4 }}</b></span><br>
 {{ status.ab9 }}<br>{{ status.b2 }}</p><br><br>
 <p v-for="status in listData" :key="status"><span><b>{{ status.ab5 }}</b></span><br>{{ status.b3 }}</p><br>
 <p v-for="status in listData" :key="status"><span><b>{{ status.ab6 }}</b></span><br>{{ status.b4 }}</p><br>
<h3 v-for="status in listData" :key="status">{{ status.r }}</h3><hr style="border-top: dashed 1px;" ><br>
            <ul>
                <li v-for="status in listData" :key="status" style="text-align:right">{{ status.hobi }}</li>
                <li v-for="status in listData" :key="status" style="text-align:right">{{ status.hobi1 }}</li>
                <li v-for="status in listData" :key="status" style="text-align:right">{{ status.hobi2 }}</li>
            </ul>
            <br>
<h3 v-for="status in listData" :key="status">{{ status.q }}</h3><hr style="border-top: dashed 1px;" />
<p v-for="status in listData" :key="status">{{ status.p }}
</p><br>
<h3 v-for="status in listData" :key="status">{{ status.ape }}</h3><hr style="border-top: dashed 1px;" />
<p v-for="status in listData" :key="status">{{ status.b5 }}
</p><br>
</div>
 <h2 v-for="status in listData" :key="status">{{ status.apa }}</h2><hr style="border: 3px solid black;">
<div class="a">
    <div class="b" style="background: grey;">
            <h3 v-for="status in listData" :key="status">&#127773;{{ status.w }}</h3><hr style="border-top: dashed 1px;" />
            <p v-for="status in listData" :key="status">{{ status.hidup }}<br>
                <ul>
                    <li v-for="status in listData" :key="status">{{ status.a }}</li>
                    <li v-for="status in listData" :key="status">{{ status.b }}</li>
                    <li v-for="status in listData" :key="status">{{ status.c }}</li>
                    <li v-for="status in listData" :key="status">{{ status.d }}</li>
                    <li v-for="status in listData" :key="status">{{ status.e }}</li>
                    <li v-for="status in listData" :key="status">{{ status.f }}</li>
                    <li v-for="status in listData" :key="status">{{ status.g }}</li>

                </ul></p><br><br>
    </div>
    <div class="b"  style="background: grey;">
            <h3 v-for="status in listData" :key="status">&#x1F341;{{ status.n }}</h3><hr style="border-top: dashed 1px;">
            <p v-for="status in listData" :key="status">{{ status.pesan }}{{ status.gf }}</p><br><br>
    </div>
    <div class="c" style="background: grey;">
      <h3>&#127836;SKILLS</h3><hr style="border-top: dashed 1px;">
      <p >Nothing&#9899;&#9899;&#9899;&#9899; &#9898; &#9898;</p>
      <p >Public Speaking&#9899;&#9899;&#9899;&#9899; &#9898; &#9898;</p>
      <p >Nothing is impossible&#9899;&#9899;&#9899;&#9899; &#9898; &#9898;</p>
    </div>
</div>

</div>
    </div>
    </div>
  </div>
</template>
<script>
import axios from 'axios'
export default {
  data(){
    return{
        listData: []
    }
  },
  mounted() {
    this.load()
  },
  methods: {
    load(){
        axios.get('http://localhost:3000/listData').then(res => {
        this.listData = res.data 
      }).catch ((err) => {
        console.log(err);
      })
    }
   }
  }
</script>
<style scoped>

* {
    box-sizing: border-box;
  }
  
  /* Create four equal columns that floats next to each other */
  .a {
    float: left;
    width: 40%;
    padding: 30px;
  }
  
  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }
  
  /* Responsive layout - makes a two column-layout instead of four columns */
  @media screen and (max-width: 600px) {
    .a  {
      width: 40%;
    }
  }
  
  /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
  @media screen and (max-width: 600px) {
    .a {
      width: 40%;
    }
  }
</style>