<template>
  <!-- Footer-->
  <div class="footer">
    <h3><b>Any questions or concerns? Contact mpark7@gmail.com</b></h3>
  </div>
</template>

<script>
    export default {
        name: "Matthew"
    }
</script>

<style scoped>
  @import url('https://fonts.googleapis.com/css?family=Great+Vibes|Open+Sans+Condensed:300|Roboto+Condensed');

  .navigating{
    margin: 0;
    font-family:'Roboto Condensed', sans-serif;
    overflow: auto;
  }

  ul {
    margin: 0;
    padding: 0;
  }

  a:hover{
    text-decoration:none;
  }

  .nav-title h1{
    width:flex;
    color:#ff6666;
    text-align:center;
    text-decoration:none;
    padding:10px;
    padding-right: 50px
  }

  .nav-ul{
    list-style-type:none;
    padding: 0px;
    float:left;
  }

  .nav-brand, .nav-list{
    display:inline-block;
    float:left;
  }

  li.navlist{
    width: flex;
    float:left;
    display:inherit;
    text-align:center;
    padding: 18px;
    padding-bottom:19px;
  }

  a li:hover {
    background-color: #d9d9d9;
  }

  .active {
    background-color: #d9d9d9;
  }
  .page-wrap{
    width:1000px;
    margin-top:25px;
    margin-left: 50px;
    position: relative;
    height:100%;
  }
  .summary{
    width:750px;
    min-height:100%;
    margin-left:200px;
    position: relative;

  }

  .summary li{
    font-size: 15px;
  }

  .sidebar {
    position: fixed;
    margin-top:150px;
    margin-left: 0px;
    font-size: 14px;
    background-color: #e6e6e6;
  }

  .sidebar li:hover{
    background-color: #d9d9d9;
  }

  .sidebar li{
    float:none;
    padding:5px;
  }

  .sidebar ul{
    list-style: none;
    width:150px;
  }

  .sidebar a{
    padding:0px;
    text-align:left;
  }
  .card{
    padding:10px;
    width:500px;
  }
  .card-text{
    line-height:150%;
  }

  table{
    width:700px;
  }

  th, td{
    padding: 3px;
    border: 1px solid #111111;
    font-size: 14px;
  }

  a, a:hover{
    color: black;
  }

  th {
    text-transform: uppercase;
    letter-spacing: 0.1em;
    text-align: left;
  }

  html {
    height: 100%;
    box-sizing: border-box;
  }
  *,
  *:before,
  *:after {
    box-sizing: inherit;
  }
  body{
    min-height:100%;
    font-family: 'Roboto Condensed', sans-serif;
    position: relative;
    margin: 0;
    padding-bottom: 6rem;
    min-height: 100%;
    color: #666666;
    background-color: #f9f8f6;
    background-position: center;
  }


  p, ol {
    font-size: 15px;
    font-weight: 500;
    line-height: 1.3em;
  }

  h1 {
    font-size: 28px;
  }

  h2 {
    font-size: 20px;
  }

  h3 {
    font-family: 'Open Sans Condensed', sans-serif;
    font-size: 18px;
  }

  h4 {
    font-family: 'Open Sans Condensed', sans-serif;
    font-size: 16px;
    font-weight: bold;
    text-decoration: underline;
  }

  h5 {
    font-family: 'Open Sans Condensed', sans-serif;
    font-size: 16px;
    font-weight: bold;
  }
  .footer {
    background-color: #d9d9d9;
    position: absolute;
    right: 0;
    bottom: 0;
    left: 0;
    padding: 10px;
    text-align: center;
  }
  .footer h3{
    font-size:16px;
  }
</style>
