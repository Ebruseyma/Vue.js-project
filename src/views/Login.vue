<template>
<article>
  <div class="Icon">
    <div class="Material-icon">
      <div class="Union">
        <div class="Material-icon-image" img src="D:\otokocassignment\otokoc\src\assets\Material-icon-image.png">
          <div class="Path">
          </div>
        </div>
      </div>
    </div>
  </div>

  <div>
  <div class="Group-1">
  <div>
    <div class="Textual">
        <div class="ICON">
          <div class="Union">
           <div class=" Material-icon_chevron-right">
             <div class="Path">
             </div>
            </div>
          </div>
        </div>
        <div class="LABEL">
        </div>
        <div class="GIRIS">
        </div>
        <div class="_Text-state" >
          
          <div class="INPUT">
          </div>
        </div>
        <div class="_Text-state" password>
          <div class="INPUT">
          </div>
        </div>
        
          </div>
        </div>
      </div>
  </div>
  
</article>
</template>

<script>
 export default{
   name='Login'
 }
</script>

<style>
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
background: #0F172A;
}

.Group-1{
  
position: absolute;
width: 463px;
height: 297px;
left: 800px;
top: 363px;



/* _Text state */

/* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 12px 8px;

position: absolute;
width: 463px;
height: 48px;
left: 800px;
top: 451px;

/* White */
background: #FFFFFF;
/* Grey / Light */
border: 1px solid #E2E8F0;
box-sizing: border-box;
border-radius: 2px;

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
left: 1124px;
top: 612px;

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


.Material-icon_chevron-right{

position: absolute;
left: -0.25%;
right: -0.21%;
top: 0%;
bottom: 0%;
}

.Path{
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

/* Body / Bold */
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
  position: absolute;
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

}

._Text-state{
  /* Auto layout */
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 12px 8px;

position: absolute;
width: 463px;
height: 48px;
left: 800px;
top: 519px;

/* White */
background: #FFFFFF;
border: 1px solid #E2E8F0;
box-sizing: border-box;
border-radius: 2px;

}

</style>