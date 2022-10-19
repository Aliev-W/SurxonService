<template>
  <section class="home">
    <div class="main">
      <div class="card">
        <img src="../assets/images/img.png" alt="">

        <button class="card-btn">Kompyuterlar</button>

      </div>
      <div class="card">
        <img src="../assets/images/img1.png" alt="">

        <button class="card-btn">Noutbuklar</button>

      </div>
      <div class="card">
        <img src="../assets/images/img2.png" alt="">

        <button class="card-btn">Kompyuterlar</button>

      </div>
      <div class="card">
        <img src="../assets/images/img.png" alt="">

        <button class="card-btn">Kompyuterlar</button>

      </div>
    </div>
  </section>
  <!-- about -->
  <section class="about">
    <h1 class="text">Xizmat kursatish turlari</h1>
    <div class="container">
      <div class="items">
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>
        <div class="item">
          <img src="../assets/images/card.png" alt="">
        </div>

      </div>

    </div>
  </section>
  <!--main  -->

  <section class="main">
    <h1 class="text">
      Hududiy filliallar
    </h1>
    <div class="container">
      <div class="left">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
      </div>
      <div class="center">
        <img src="../assets/images/doc.png" alt="">
      </div>
      <div class="right">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
      </div>
    </div>
  </section>  
  <!--  -->
  <section class="main">
    <h1 class="text">
      Sertifikatlar
    </h1>
    <div class="container">
      <div class="left">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
      </div>
      <div class="center">
        <img src="../assets/images/doc.png" alt="">
      </div>
      <div class="right">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
        <img src="../assets/images/doc.png" alt="">
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>

<style lang="scss" >
 .text{
    width: 860px;
    height: 74px;
    background: #242754;
    color: #ffff;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 10px;
    border: none;
    line-height: 46px;
    font-size: 36px;
    margin: 93px auto;
   }
    .home{
        max-width: 2000px;
        width: 100%;
        margin: 0 auto;
      

      .main{
        width: 100%;
        display: flex;
        gap: 30px;
        padding: 0px 10px;
        .card{
          border-radius: 15px;
          width: 460px;
         
        
            position: relative;
          img{
            width: 100%;
            height: 100%;
            border-radius: 5px;
           
          }
          .card-btn{
            width: 200px;
            border: none;
            width: 200px;
            height: 60px;
            background:#242754;
            opacity: 0.9;
            color: #fff;
            font-family: 'Roboto';
            font-weight: 400;
            font-size: 16px;
            line-height: 18px;
            border-radius: 10px;
            position: absolute;
            top: 700px;
            left: 0;
          }
        }
         :hover{
            scale: 1.05;
            transition: 1s;
          }

      }
    }

    .about{
   max-width: 2000px;
   width: 100%;
   margin: 0 auto;

   
   .container{
      max-width: 1800px;
      width: 100%;
      margin: 0 auto;

      .items{
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
        margin-left: 100px;
        margin-bottom: 34px;

        .item{
          width: 509px;
          height: 509px;
          img{
            width: 100%;
            height: 100%;
            border-radius: 10px;
           
          } :hover{
              transform: rotate(1deg);
              scale:(1.01);
              transition: 1s;
          }
        }
      }
      
   }
   
 }
 .main{
  min-width: 2000px;
  width: 100%;
  margin: 0 auto;
  .container{
    max-width: 1800px;
    width: 100%;
    margin:0 auto;
    margin-left: 120px;

      display: flex;
      align-items: center;
      gap: 20px;

      .center{
 
        img{
          width: 1000px;
          height: 840px;
          
        }
      }
      .left{
       display: flex;
       flex-direction: column;
       gap: 14px;
        img{
   
          width: 300px;
          height: 204px;
        }
      }
      .right{
        display: flex;
       flex-direction: column;
       gap: 14px;
        img{
          height: 204px;
          width: 300px;
        }
      }
      
    
  }

 }

</style>
