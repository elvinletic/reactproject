# reactproject


/* /* CSS */
/*https://codepen.io/AlexWarnes/pen/jXYYKL*/

@keyframes spin {
  from {
    transform: rotate(0);
  }
  to{
    transform: rotate(359deg);
  }
}

@keyframes spin3D {
  from {
    transform: rotate3d(.5,.5,.5, 360deg);
  }
  to{
    transform: rotate3d(0deg);
  }
}

/* GRID STYLING */

* {
  box-sizing: border-box;
}

body {
  min-height: 100vh;
  background-image: url('https://res.cloudinary.com/dc4stsmlc/image/upload/v1570612478/Codepen/space_sanxvu.jpg');
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.spinner-box {
  margin-left: 440px;
  width: 300px;
  height: 300px;
  display: flex;
  align-items: center;
  background-image: url('https://miro.medium.com/max/630/0*8UOb6jaS4MJZ2S3S.jpg');
  /*animation: spin 84s linear 0s infinite;*/
  background-size: cover;
  border-radius: 50%;
  box-shadow: -2px -2px 4px 4px rgba(0, 0, 0, 0.75),
    inset 24px 4px 10px 2px black;	
}

/* SPINNING CIRCLE */

.circle-border {
  width: 150px;
  height: 150px;
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  background: rgb(63,249,220);
  background: linear-gradient(0deg, rgba(63,249,220,0.1) 33%, rgba(63,249,220,1) 100%);
  animation: spin .8s linear 0s infinite;
}

.circle-core {
  width: 200%;
  height: 100%;
  background-color: #1d2630;
  border-radius: 50%;
}

:root {
  --size: 60vh;
  --borderS: calc(var(--size) / 10);
  --ballSize: calc(var(--size) / 5);
  --rightCorrected: calc(var(--size) / 13.33);
}

/*.spinner-box::before {
  content: "";
  position: absolute;
  bottom: 50%;
  right: var(--rightCorrected);
  width: var(--ballSize);
  height: var(--ballSize);
  transform: translateY(-50%);
  background: lightgray;
  box-shadow: -2px -2px 4px 4px rgba(0, 0, 0, 0.75),
    inset 6px 4px 10px 2px black;
  border-radius: 50%;
}
 
/*https://codepen.io/BlackStar1991/pen/poyMoeN*/ */


/*
--------------------------------------------------------------
*/

<!-- HTML -->
<div class="spinner-box">
  
</div>



 */
