<template>
<body>
<article>
  <div class="Login">
  <div class="Icon">
    <div class="Material-icon">
      <div class="Union">
        <div class="Material-icon-image">
          <div class="Path"> </div>
          </div>
        </div>
      </div>
    </div>



  <div class="Group-1">
    <div class="Textual"> 
      <div class="ICON"> 
        <div class="Union">  
          <div class="Material-icon_chevron-right"> </div>
          </div>
          </div>
         
    <div class="LABEL"> 
         <div class="btn btn-primary pull-right" @click="login()"  v-on:keyup.enter="login" type="submit" >Giriş Yap</div>
     </div>
      </div>
    <div class="GIRIS"> </div>
    <div class="_Text-state" > <input type="text" v-model="username" class="INPUT" id="username" placeholder="Email / Kullanıcı adı" >
        <label for="username"></label> 
        </div>
    <div class="_Text-state1" > 
      <input type="password" id="Password" class="INPUT" placeholder="Şifre"  v-model="password"  >
        <label for="Password"></label>   
    </div>
  </div>
  


<div class="Error-Message" >
<div class="Icon2" >
<div class="Material-icon" >
  <div class="Union" >
    <div class="Material-icon_close" >
      <div class="Path" ></div>
    </div>
  </div>
</div>
</div>

<div class="Frame-2" >
  <div class="Frame-1" >
        <div class="Title" ><h1> Hata </h1> </div>
    <div class="Description"><p> Kullanıcı Adınız veya Şifreniz Hatalı  </p></div>
  </div>
  <div class="_Icon" >
    <div class="Union" >
      <div class="Material-icon_error" >
        <div class="Path" img alt="material-error" src="../assets/Path.png" /> </div>
      </div>
    </div>
  </div>
<div class="Line-1" > </div>
</div>

<div class="Otokoc-Otomotiv-Logo-1"> </div>
</div>
</article>
</body>
</template>

<script>
 export default {
 methods:{
   login(){
   this.$router.push('/dashboard'); 
   this.$router.push({name:'dashboard', params: {id: '[paramdata]'}}); 

      }
  }
  
}
</script>

<style>
.Login{

position: relative;
width: 1440px;
height: 1024px;

background: #FFFFFF;
}

.INPUT{
  position: static;
width: 447px;
height: 24px;
left: calc(50% - 447px/2);
top: calc(50% - 24px/2);

/* Body / Default */
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height:  20px;
/* identical to box height, or 150% */
font-feature-settings: 'tnum' on, 'lnum' on;

color: #94A3B8;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 1;
margin: 0px 0px;
border: none;
}
.Icon{
position: absolute;
width: 720px;
height: 1024px;
left: 0px;
top: 0px;
background: #E2E8F0;


}
.Material-icon{
position: absolute;
width: 40px;
height: 40px;
left: calc(50% - 40px/2);
top: calc(50% - 40px/2);
}
.Material-icon-image{
  position: absolute;
left: -0.25%;
right: -0.21%;
top: 0%;
bottom: 0%;

}
.Union{
position: absolute;
width: 40.18px;
height: 40px;
left: -0.1px;
top: 0px;
background: #94A3B8;

}
.Path{
  position: absolute;
left: 12.5%;
right: 12.5%;
top: 12.5%;
bottom: 12.5%;
background:url("../assets/Material-icon-image.png");

}

.Group-1{
  
position: absolute;
width: 463px;
height: 297px;
left: 800px;
top: 363px;


/* Auto layout */
flex-direction: row;
align-items: flex-start;
padding: 12px 8px;

position: absolute;
width: 463px;
left: 800px;
top: 451px;

}

.Textual{
  display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 12px 24px;

position: absolute;
width: 139px;
height: 48px;
left: 340px;
top: 250px;

/* Black */
border: 1px solid #0F172A;
box-sizing: border-box;
border-radius: 2px;

}

.ICON{
  position: static;
width: 18px;
height: 18px;
left: 98.5px;
top: calc(50% - 18px/2);


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 0px 6px;
}

.Union{
  position: absolute;
width: 18.08px;
height: 18px;
left: -0.05px;
top: 0px;

/* Black */
background: #0F172A;

}


.Group-1.Textual.ICON.Union.Material-icon_chevron-right{

position: absolute;
left: -0.25%;
right: -0.21%;
top: 0%;
bottom: 0%;
}

.Group-1.Textual.ICON.Union.Material-icon_chevron-right.Path{
position: absolute;
left: 35.79%;
right: 33.33%;
top: 25%;
bottom: 25%;

/* Black */
background: #0F172A;
}


.LABEL{
position: static;
left: 22.5px;
right: 46.5px;
top: 25%;
bottom: 25%;
font-family: Inter;
font-style: normal;
font-weight: bold;
font-size: 16px;
line-height: 24px;
/* identical to box height, or 150% */
display: flex;
align-items: center;
text-align: center;
font-feature-settings: 'tnum' on, 'lnum' on;


/* Black */
color: #0F172A;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 6px;
}

.GIRIS{
width: 59px;
height: 48px;
left: 808px;
top: 363px;

font-family: Inter;
font-style: normal;
font-weight: 900;
font-size: 24px;
line-height: 48px;
/* identical to box height, or 200% */
display: flex;
align-items: center;
font-feature-settings: 'tnum' on, 'lnum' on;

/* Black */
color: #0F172A;
background:url("../assets/Giris.jpg") no-repeat;

}

._Text-state1{
  /* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 12px 8px;
position: absolute;
width: 463px;
height: 48px;
left: 10px;
top: 155px;

/* White */
background: #FFFFFF;
border: 1px solid #E2E8F0;
box-sizing: border-box;
border-radius: 2px;
}

._Text-state{
  display: flex;
flex-direction: row;
align-items: flex-start;
padding: 12px 8px;
position: absolute;
width: 463px;
height: 48px;
left: 10px;
top: 90px;

/* White */
background: #FFFFFF;
/* Grey / Light */

border: 1px solid #E2E8F0;
box-sizing: border-box;
border-radius: 2px;
}



.Error-Message{

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px 16px 0px 0px;

position: absolute;
width: 380px;
height: 80px;
left: calc(50% - 380px/2 + 490px);
top: 904px;

/* Grey / Lightest */
background: #F8FAFC;
border-radius: 4px;
}

.Icon2{
  display: flex;
flex-direction: row;
align-items: flex-start;
padding: 16px 0px 0px;

position: static;
width: 24px;
height: 80px;
left: 340px;
top: 0px;

opacity: 0.2;

/* Inside auto layout */

flex: none;
order: 2;
align-self: stretch;
flex-grow: 0;
margin: 0px 16px;
}

.Line-1{

position: static;
width: 70px;
height: 0px;
left: 0px;
top: 0px;

/* UI / Error / Dark */
border: 3px solid #F43F5E;
transform: rotate(90deg);

/* Inside auto layout */
flex: none;
order: 0;
align-self: center;
flex-grow: 0;
margin: 35px -40px;
border-radius:5;
}

.Frame-2{

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 16px 0px;

position: static;
width: 308px;
height: 80px;
left: 16px;
top: 0px;


/* Inside auto layout */
flex: none;
order: 1;
flex-grow: 1;
margin: 0px 16px;
}

._Icon{

position: static;
width: 24px;
height: 24px;
left: calc(50% - 24px/2 - 142px);
top: 16px;


/* Inside auto layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 8px;
}

.Description{

position: static;
width: 276px;
height: 5px;
left: 0px;
top: 50px;

/* Body / Default */
font-family: Inter;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 24px;
/* identical to box height, or 150% */
display: flex;
align-items: center;
font-feature-settings: 'tnum' on, 'lnum' on;

/* Black */
color: #0F172A;


/* Inside auto layout */
flex: none;
order: 1;
align-self: stretch;
flex-grow: 0;
margin: 0px 0px;

}

.Title{

position: static;
width: 276px;
height:30px;
left: 0px;
top: 0px;
}

.Otokoc-Otomotiv-Logo-1{
  
position: absolute;
width: 165px;
height: 33px;
left: 1235px;
top: 40px;

background: url('../assets/Otokoc-Otomotiv-Logo11.png');
}
</style>