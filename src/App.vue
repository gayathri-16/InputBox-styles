<template>
  <div>
    <link  rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.css" />
   <link href="https://fonts.googleapis.com/css2? amily=Baloo+Thambi+2:wght@500&family=Montaga&family=Tajawal&display=swap" rel="stylesheet">
   <link href="https://fonts.googleapis.com/css2?family=Philosopher:wght@400;700&display=swap" rel="stylesheet">
   <link href="https://fonts.googleapis.com/css2?family=Courgette&family family=Roboto:wght@300&display=swap" rel="stylesheet">
    <h1 class="header">Inputs</h1>
      
    <div class="button-types">
      
      <h2 class="buttons">Typography</h2>
      <h2 class="buttons">Grid</h2>
      <h2 class="buttons">Buttons</h2>
      <h2 class="buttons"><b style="color:rgb(5, 13, 63);">Inputs</b></h2>
      
    </div>

<div class="first-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input / <i class="fas fa-angle-right"></i> </h3>
  <h3 class="title in-hov"> & : hover </h3> 
  <h3 class="title in-foc "> & : focus </h3> 
  <br> <br>
  <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
  <input  type="text" class="normal" placeholder="Placeholder">
  <label for="" class="label label-one">Label</label>
  <input  type="text" class="normal effect-input" placeholder="Placeholder">
  <label for="" class="label label-two l-foc" style="color:rgb(0, 102, 255);">Label</label>
  <input  type="text" class="normal focus-input "  placeholder="Placeholder">
 </div> <br>

 <div class="second-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input error / <i class="fas fa-angle-right"></i> </h3>
  <h3 class="title in-hov" style="margin-left:12.4rem;"> & : hover </h3> 
  <h3 class="title in-foc "> & : focus </h3> 
  <br> <br>
  <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
  <input  type="text" class="normal err" placeholder="Placeholder"> 
  <label for="" class="label label-one">Label</label>
  <input  type="text" class="normal effect-input" placeholder="Placeholder">
  <label for="" class="label label-two e-foc" style="color:red">Label</label>
  <input  type="text" class="normal focus-input err-foc" placeholder="Placeholder">
 </div> <br>

<div class="third-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input disabeld / <i class="fas fa-angle-right"></i> </h3> <br> <br>
    <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
  <input  type="text" class="normal disabel" placeholder="Placeholder">
 </div>

<div class="second-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input helperText="Someinteresting text " / <i class="fas fa-angle-right"></i> </h3>
  <h3 class="title" style="margin-left:6rem;"> <i class="fas fa-angle-left"></i> Input helperText="Someinteresting text " error / <i class="fas fa-angle-right"></i> </h3>
  <br> <br>
  <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
   <input  type="text" class="normal" placeholder="Placeholder">
   <label for="" class="label label-one e-foc"  style=" margin-left:30rem; color:red;">Label</label> 
    <input  type="text" class="normal focus-input err-foc"  placeholder="Placeholder"> <br> <br><br><br> 
 <h3 class="title x" style="font-size:14px;"> Some interesting text</h3>
  <h3 class="title some " style="font-size:14px; margin-left:24rem;">Some interesting text </h3>
</div> 
<div class="second-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input startIcon / <i class="fas fa-angle-right"></i> </h3>
  <h3 class="title" style="margin-left:21rem;"> <i class="fas fa-angle-left"></i> Input endIcon / <i class="fas fa-angle-right"></i> </h3>
  <br> <br>
  <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
   <input  type="text" class="normal input-ic" placeholder="Placeholder"><i class="fas fa-phone-alt" style="margin-top:2.5rem; margin-left:-2rem; position:absolute; color:gray; font-size:20px; "></i>
   <label for="" class="label label-one e-foc"  style=" margin-left:30rem; color:red;">Label</label> 
    <input  type="text" class="normal focus-input err-foc"  placeholder="Placeholder"><i class="fas fa-lock" style="margin-top:2.5rem; margin-left:8rem; position:absolute; color:gray; font-size:20px; "></i> <br> <br><br><br> 
 </div> 

<div class="third-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input value="text" / <i class="fas fa-angle-right"></i> </h3> <br> <br>
    <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
  <input  type="text" class="normal" placeholder="Placeholder">
 </div>
  
  <div class="second-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input size="sm" / <i class="fas fa-angle-right"></i> </h3>
  <h3 class="title" style="margin-left:21rem;"> <i class="fas fa-angle-left"></i> Input size="md" / <i class="fas fa-angle-right"></i> </h3>
  <br> <br>
  <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
   <input  type="text" class="normal" placeholder="Placeholder" style="width:190px; height:15px;">
   <label for="" class="label label-one e-foc"  style=" margin-left:30rem;">Label</label> 
    <input  type="text" class="normal focus-input err-foc"  placeholder="Placeholder" style="width: 180px;height:35px;"> 
 </div> 
  <br>
  <div class="third-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input fullwidth / <i class="fas fa-angle-right"></i> </h3> <br> <br>
    <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
  <input  type="text" class="normal form-field" placeholder="Placeholder" style="width:900px;">
 </div>
 <div class="third-row">
  <h3 class="title"> <i class="fas fa-angle-left"></i> Input multiline row="4" / <i class="fas fa-angle-right"></i> </h3> <br> <br>
    <label for="" class="label" style="font-family: 'Courgette', cursive;">Label</label>
  <input  type="text" class="normal multiline" placeholder="Placeholder" >
 </div> <div style="height:20rem;"><br><br><br></div>
   </div>
</template>

<script>
  export default {
    
  }
</script>

<style>

.header{
  text-align:center;
  font: 40px ;
  font-family: 'Fugaz One', cursive;
  font-weight:700px;
  transform-style:preserve-3d;
  font-weight:100;
  text-shadow: 0 0 10px rgba(255,255,255, 1),
               0 0 20px rgba(255,255,255, 1),
               0 0 40px rgba(255,255,255, 1),
               0 0 80px rgba(255,255,255, 1),
               0 0 160px rgba(255,255,255, 1);
-webkit-animation: glow 1s ease-in-out infinite alternate;
  -moz-animation: glow 1s ease-in-out infinite alternate;
  animation: glow 1s ease-in-out infinite alternate;
}

@keyframes glow {
  from {
    text-shadow: 0 0 10px rgb(16, 218, 245), 0 0 20px rgb(16, 128, 148), 0 0 30px #00d7e6, 0 0 40px #a7fdfd, 0 0 20px #8dd6f3, 0 0 20px #0ba7ce, 0 0 30px #1dbfdb;
  }
  
  to {
    text-shadow: 0 0 10px rgb(12, 201, 226), 0 0 30px #0b97b9, 0 0 40px #107ba5, 0 0 50px #074597, 0 0 60px #1c0ed4, 0 0 40px #1554dd, 0 0 50px #072d75;
  }

}

.button-types{
  margin:5rem;
 
}
.buttons{
font-size:24px;
color:rgb(75, 75, 75);
line-height: 70px;
 font-family: 'Roboto', sans-serif;
 letter-spacing: 1px;
}
.first-row{
   margin-left:30rem;
   margin-top:-25rem;
}

.title{
  font-size:20px;
  font-family:'Tajawal', sans-serif;
 display:inline;
 text-align:center;
 color:rgb(32, 32, 32);
   text-shadow: 2px 2px 2px rgb(114, 114, 114);
}
.in-hov{
 margin-left:15rem;
}
.in-foc{
margin-left:16.3rem;

}
.label{
  display:inline;
  font-family: 'Courgette', cursive;
  color:rgb(43, 41, 20);
    text-shadow: 2px 2px 2px rgb(85, 84, 83);

}
.label-one{
   margin-left:18.5rem;
}
.label-two{
   margin-left:19rem;
}
.normal{
  margin-left:-3rem ;
}

.effect-input{
 font-size:20px;
 margin-left:-3rem;
  
}
.effect-input:hover{
  border:2px solid black;
}
.focus-input{margin-left:-3rem;}
.focus-input:focus{
  border-color:rgb(0, 102, 255);
  box-shadow: 0 5px 15px34r rgb(0,0,0,.5);        
  z-index:2;      
}
.label-two:hover{
  color:rgb(0, 102, 255);
}
input{
  display: inline;
  position:absolute;
  width:180px;
  height:25px;
  border-radius:10px;
  border-style:none;
  border:2px solid gray;
  font-family: 'Baloo Thambi 2', cursive;
  font-size:20px;
  padding:12px;
  outline:none;
  margin-top:1.5rem;
}
::-webkit-input-placeholder{
  
  color:#a0a0a0;
    
}
.input-ic::placeholder{
padding-left:2rem;
}
.multiline{
height:100px;
text-overflow: clip;
}
.multiline::placeholder{
  padding-left:1rem;

  position:fixed;
}
.icon{
  margin-left:-1rem;
  margin-top:0.8rem;
}
.second-row{
   margin-left:30rem;
   margin-top:8rem;
}
.err{
  border:2px solid rgb(255, 38, 38);
}
.err-foc:focus{
  border:2px solid rgb(255, 38, 38);
}
.some{
  color:red;
  opacity:1;
}
.third-row{
  margin-left:30rem;
   margin-top:8rem;
}
.disabel{
  background:rgb(219, 219, 219);
  color:gray;
}
h6{
  color:black;
  font-size:14px;
  margin-top:5rem;
  display:inline;
}

.form-field{
border:0;
border-bottom:2px solid #9b9b9b;
outline:0;
transition: border-color 0.2s;


} 
.form-field::placeholder{
  color:transparent;
}

.form-field:focus{
  padding-bottom:6px;
  font-weight:700;
  border-width:3px;
  border-image:linear-gradient(to right,#ff0062,#00ffff);
  border-image-slice:1;

}
.form-field::placeholder{
  position:absolute;
  top:0;
  display:block;
  transition:0.2s;
  font-size:1rem;
  color:#2afadf;
  font-weight:lighter;
}
</style>
 