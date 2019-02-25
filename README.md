# nhabCSSFW
nhab css framework
/*----------------- font ------------------------------------------*/
@font-face{
font-family:'b nazanin';
src:url('../fonts/BNazanin.eot?#')format('eot'),
url('../fonts/BNazanin.woff')format('woff'),
url('../fonts/BNazanin.ttf')format('ttf');
}
@font-face{
font-family:'b titr';
src:url('../fonts/BTitrBold.woff')format('woff'),
url('../fonts/B-Titr.ttf')format('ttf');
}
@font-face{
font-family:'b yekan';
src:url('../fonts/BYekan.eot?#')format('eot'),
url('../fonts/BYekan.woff')format('woff'),
url('../fonts/BYekan.ttf')format('ttf');
}

/*------------------------ tags ---------------------------------------------*/

 html,body,div,span,table,tr,td{margin: 0;    padding: 0;}
html { font-size: 14px;    height: 100vh;}
body { position:absolute; top:0; bottom:0; right:0; left:0; background:#eeeeff; }
strong{font-family:'b yekan';font-size:12pt;margin:0;padding:0;}
td{vertical-align:top}
pre{font-family:'b yekan';font-size:12pt;}
/*------------------------ classes ------------------------------------------*/
.title{font-family:'b titr';font-size:52px;margin:10px 10px;padding:0; text-align:center;}
.subtitle{font-family:'b nazanin';font-size:24px;margin:0;padding:0;}
.text{font-family:'b nazanin';font-size:20px;margin:0;padding:0;}
   /* size and locatiom */
.fullwidth{width:100%;}
.block{display:block}
.pre{ white-space: pre;}
.rtl{ direction: rtl;}
.inline{display: inline-block;}

.top{vertical-align:top}
.vcenter{vertical-align:middle}
.bottom{vertical-align:bottom}

.left {  text-align: left;}
.right {  text-align: right;}
.hcenter{ text-align:center}
.center{  vertical-align:middle;  text-align:center} 

.margins{margin: 25px 0 25px;}
.paddings{ padding: 2rem 3rem 1rem;}
   /* controls */
.button {
  background-color: #004488;
  border: none;
  color: white;
  padding: 15px 32px;
  margin:4px 4px 4px 4px;
  text-align: center;
  text-decoration: none;

  font-size: 16px;
  font-family:'b yekan';
  width:110px;height:16px;
  display: inline-block; 
}
.button:hover {
  background-color: #004444;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    overflow: hidden;
    margin-bottom: 2rem;
}
.card {
   /*background: #EAEAEA;*/
   padding: 2rem 3rem 1rem;
}
.card-header {
    font-weight: 600;
    margin: 0;
    padding: 2rem 3rem 1rem;
}
.card-body {
    padding: 0 3rem 2rem 3rem;
    min-height: 100px;
}
.card-footer {
    display: flex;
    align-items: stretch;
    border-top: 1px solid #dbdbdb;
    flex: 1;
}
