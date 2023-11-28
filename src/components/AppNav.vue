<script>

</script>

<template>
 <div class="maindiv">
    <div class="left">
        <h1>deskpass</h1>
    </div>
    <div class="center">
        <ul>
            <li><a href="">Find Space</a></li>
            <li><a href="">Solutsion</a></li>
            <li><a href="">Pricing</a></li>
            <li><a href="">Pricing</a></li>
        </ul>
    </div>
    <div class="right">
        <a href="" class="first" >Get started</a>
        <span class="second" >or</span>
        <a href="" class="third" >login</a>
    </div>
  </div>
</template>

<style scoped lang="scss">
.maindiv{
    height:100px;
    width:100%;
    display: flex;
    .left{
        width:33%;
        display: flex;
        justify-content: center;
        align-items: center;
        color: black;
    }
    .center{
        width:34%;
        
        ul{
            margin:0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100%;
            list-style-type: none;
            
            a{
                text-decoration: none;
                color: black;
                font-size:30px;
                
            }
        }
    }
    .right{
        width:33%;
        display: flex;
        align-items: center;
        justify-content:center;
        gap:20px;
        a{
                text-decoration: none;
                color: black;
                
            }
        .first{
            background-color: blue;
            padding:10px 20px;
            border-radius:50px;
            color: white;
        }
        .first:hover{
            background-color:black;
            margin-bottom: 10px;
        }
        .third{
            color: blue;
        }
        .third:hover{
            color: black;
        }
    }
}

</style>
