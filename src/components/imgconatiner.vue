<script>

</script>

<template>
<div class="main">
    <div class="bgimg">
      <div class="titleimg">
       <h1>Work from <span>anywhere</span>
       </h1>
      </div>   
      <div class="textimg">    
      <p>We connect people to the amazing <span>workspace</span> they need today <br>to help conmpanies creathe the hybrid <span>workspace</span> of tomorrow</p>
      </div>
      <div class="search">
      <input type="search">
      </div>  
    </div>
</div>

</template>


<style scoped lang="scss">
.main{
    width: 100%;
    .bgimg{
        height:700px;
        width: 100%;
        background-color:black;
        .titleimg{
            display: flex;
            justify-content: center;
            padding-top: 150px;
           
            h1{
                color: white;
                font-size: 50px;
            }
            span{
                text-decoration:underline blue;
                
            }
        }
        .textimg{
            display:flex ;
            justify-content: center;
            font-size: 25px;
            color: white;
            span{
                text-decoration:underline ;
            }
            
            }
        .search{
            display: flex;
            justify-content: center;
           
        }  

        }    
    }

</style>