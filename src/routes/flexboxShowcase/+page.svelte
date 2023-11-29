<body>
<div class="container">
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</div>
</body>
<style>
  body {
    background-color: black;
  }
  .container {
    overflow: hidden;
    width: 100%;
    display: flex;
    justify-content: center;
    height: 500px;
    gap: 20px;
    transform: translateY(10vh);
}
    .container div {
      margin: 8px;
      flex: 0 0 120px;
      border-radius: 0.5rem;
      transition: 0.3s ease-in-out;
      cursor: pointer;
      box-shadow: 1px 5px 15px #1e0e3e;
      position: relative;
      overflow: hidden;

      &:nth-of-type(1) {
        background: url("pics/weme1.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(2) {
        background: url("pics/weme2.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(3) {
        background: url("pics/weme3.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(4) {
        background: url("pics/weme4.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(5) {
        background: url("pics/weme5.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(6) {
        background: url("pics/weme6.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(7) {
        background: url("pics/weme7.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(8) {
        background: url("pics/weme8.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(9) {
        background: url("pics/weme9.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(10) {
        background: url("pics/weme10.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(11) {
        background: url("pics/weme11.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(12) {
        background: url("pics/weme12.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(13) {
        background: url("pics/weme13.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(14) {
        background: url("pics/weme14.jpg") no-repeat 50% / cover;
      }
      &:nth-of-type(5) {
        background: url("pics/weme5.jpg") no-repeat 50% / cover;
      }
      &:hover {
        flex: 0 0 240px;
        box-shadow: 1px 3px 15px #7645d8;
      }
    }
  
</style>
