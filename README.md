# css

/* 1. google font*/
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap');
 body {
	font-family: 'Lato', sans-serif;
	font-weight: normal;
	font-style: normal;
	margin: 0;
}
.img {
	max-width: 100%;
	transition: all 0.3s ease-out 0s;
}
.bg-black{
	background: #1f1d1d;
}
.bg-blc{
	background: #2d2c2c;
}
.bg-gray{
	background: #e5e2e2;
}
.bg-copyright{
	background: #200404;
}
.f-left {
	float: left
}
.f-right {
	float: right
}
.fix {
	overflow: hidden
}
a,
.button {
	-webkit-transition: all 0.3s ease-out 0s;
	-moz-transition: all 0.3s ease-out 0s;
	-ms-transition: all 0.3s ease-out 0s;
	-o-transition: all 0.3s ease-out 0s;
	transition: all 0.3s ease-out 0s;
}
a:focus,
.button:focus {
	text-decoration: none;
	outline: none;
}
a:focus,
a:hover,
.portfolio-cat a:hover,
.footer -menu li a:hover {
	color: #2B96CC;
	text-decoration: none;
}
a,
button {
	color: #1696e7;
	outline: medium none;
}
button:focus,input:focus,input:focus,textarea,textarea:focus{outline: 0}
.uppercase {
	text-transform: uppercase;
}
.capitalize {
	text-transform: capitalize;
}
h1,
h2,
h3,
h4,
h5,
h6 {
	font-family: 'Lato', sans-serif;
	font-weight: normal;
	color: #313131;
	margin-top: 0px;
	font-style: normal;
	font-weight: 400;
	text-transform: normal;
}
h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
	color: inherit;
}
h1 {
	font-size: 40px;
	font-weight: 500;
}
h2 {
	font-size: 35px;
}
h3 {
	font-size: 28px;
}
h4 {
	font-size: 22px;
}
h5 {
	font-size: 18px;
	margin-right: 15px;
}
h6 {
	font-size: 16px;
}
ul {
	margin: 0px;
	padding: 0px;
}
li {
	list-style: none
}
p {
	font-family: 'Lato', sans-serif;
	font-size: 14px;
	font-weight: normal;
	line-height: 24px;
	color: #7e7e7e;
	margin-bottom: 15px;
}
 
label {
	color: #7e7e7e;
	cursor: pointer;
	font-size: 14px;
	font-weight: 400;
}
*::-moz-selection {
	background: #d6b161;
	color: #fff;
	text-shadow: none;
}
::-moz-selection {
	background: #444;
	color: #fff;
	text-shadow: none;
}
::selection {
	background: #444;
	color: #fff;
	text-shadow: none;
}
*::-moz-placeholder {
	color: #555555;
	font-size: 14px;
	opacity: 1;
}
*::placeholder {
	color: #555555;
	font-size: 14px;
	opacity: 1;
}
.theme-overlay {
	position: relative
}
.theme-overlay::before {
	background: #1696e7 none repeat scroll 0 0;
	content: "";
	height: 100%;
	left: 0;
	opacity: 0.6;
	position: absolute;
	top: 0;
	width: 100%;
}
.separator {
	border-top: 1px solid #f2f2f2
}
/* button style */

.btn {
	
	background: #ffae00 none repeat scroll 0 0;
	border: medium none;
	border-radius: 4px;
	color: #fff;
	cursor: pointer;
	display: inline-block;
	font-size: 13px;
	font-weight: 600;
	letter-spacing: 1px;
	line-height: 1;
	margin-bottom: 0;
	padding: 10px 25px;
	text-align: center;
	text-transform: uppercase;
	touch-action: manipulation;
	transition: all 0.3s ease 0s;
	vertical-align: middle;
	white-space: nowrap;
}
.theme-btn {
	background: #EF476F;
	width: 100px;
	height: 40px;
	border-radius: 5px;
	display: flex;
	align-items: center;
	justify-content: center;
	color: #fff;
}
.load-btn{
	background: #ffae00;
    width: 137px;
    height: 45px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
	text-transform: uppercase;
}
.load-btn:hover{
	background: transparent;
  border: 2px solid #ffae00;
  color:  #ffae00;;
}

.breadcrumb > .active {
	color: #888;
}
.owl-carousel .owl-nav div {
	background: rgba(255, 255, 255, 0.8) none repeat scroll 0 0;
	height: 40px;
	left: 20px;
	line-height: 40px;
	opacity: 1;
	position: absolute;
	text-align: center;
	top: 100%;
	transform: translateY(10%);
	transition: all 0.3s ease 0s;
	visibility: visible;
	width: 40px;
}
.owl-carousel .owl-nav div.owl-next {
	left: auto;
	right: 20px;
}
 
/* scrollUp */
#scrollUp {
	background: #ffae00;
	height: 35px;
	width: 35px;
	right: 50px;
	bottom: 77px;
	color: #fff;
	font-size: 20px;
	text-align: center;
	border-radius: 10%;
	font-size: 20px;
	line-height: 34px;
}
#scrollUp:hover {
	background: #444;
	border: 2px solid #ffae00;
	border-radius: 10px;
}
/* icon-style */
.fas.fa-ellipsis-h {
	font-size: 20px;
	display: flex;
	justify-content: flex-end;
	cursor: pointer;
}

/*header-area-start*/
  
  .theme-btn {
	background: #FFAE00;
	width: 100px;
	height: 36px;
	border-radius: 8px;
	display: flex;
	align-items: center;
	justify-content: center;
	color: #0e0e0e;
  } 
  /* header-area-end */ 
  .banner-img img {
	width: 100%;
	height: 60vh;
}
/* banner */
.banner-img {
	width: 100%;
}
/* sale-area */
.sale-first-img img {
	width: 100%;
	margin-bottom: 30px;
}
.sale-second-img img {
	width: 100%;
}
/* releases-area */
.releases-title h5 {
	color: #fff;
	font-size: 36px;
	text-align: center;
	margin-bottom: 50px;
	text-transform: uppercase; 
}
.new-area2 {
	border: 2px solid #FFAE00;
	padding: 27px;
	border-radius: 14px;
	margin-right: 15px;
}
.new-content.content h5 {
	color: #fff;
}
.card img {
	padding: 16px;
}
.card-body h5 {
	color: #e3e3e3;
	font-size: 16px;
	text-transform: uppercase;
}
.card-body span {
	color: #ffae00;
}
.card-icon {
	display: flex;
	margin-top: 15px;
	justify-content: space-between;
}
.fas.fa-heart {
	color: #e4508f;
}
.card-icon span {
	color: #fff;
	margin-left: 10px;
}
 
.card-icon.content span {
	color: #fff;
	font-weight: bold;
}

 /* owl-button */
 /* relese owl carousel */
.release-active .owl-nav div {
	background: #FFAE00;
	width: 35px;
	height: 30px;
	position: absolute;
	z-index: 9;
	color: #fff;
	text-align: center;
	line-height: 30px;
}

.release-active .owl-nav div.owl-next {right:-12px; left:auto;}

.release-active .owl-dots {
	text-align: center;
	margin-top: -20px;
	z-index: 999;
	position: relative;
	bottom: 40px;
}


.release-active .owl-dot.active {
	background: #fff;
	color: #FFAE00;
}
.owl-nav {
	position: absolute;
	top: 100%;
	left: 90%;
	text-align: center;
	z-index: 999;
}
.owl-nav button {
	border: 1px solid #222 !important;
	background: #fff !important;
	height: 40px;
	width: 40px;
	color: #222 !important;
	border-radius: 50%;
	font-size: 34px !important;
	margin: 0 10px;
}

/* popular-item-area */
 
 .popular-title h5 {
	color: #333d45;
	text-transform: uppercase;
	font-size: 36px;
	font-weight: 400;
	text-align: center;
	margin-bottom: 22px;

}
.popular-menu ul{
	padding: 0;
	margin: 0;
	list-style: none;
	text-align: center;
	margin-bottom: 50px;
}
.popular-menu ul li{
	display: inline-block;
margin: 0 10px;
	margin-bottom: 10px;
}
.popular-menu ul li a {
	color: #1f1d1d;
	font-size: 16px;
	padding: 7px;
	text-transform: uppercase;
	transition: .3s;
	position: relative;
}
.popular-menu ul li a:hover {
	border: 2px solid #FFAE00;
	border-radius: 30px;
}
.popular-items.item {
	margin-top: 20px;
} 
.new-area {
	border: 2px solid #FFAE00;
	padding: 27px;
	border-radius: 14px;
	transition: .3s;
}
.new-area:hover {
	box-shadow: 0px 15px 30px 0px rgba(0, 3, 143, 0.1);
    border-color: transparent;
 
}
img {
	width: 100%;
}
.new-content h5 {
	color: #1f1d1d;
}
.new-img {
	margin-bottom: 22px;
}
.new-content span {
	color: #FFAE00;
}
.fas.fa-heart {
	color: #E4508F;
}
.card-icon span {
	color: #000;
	margin-left: 10px;
}
.card-icon {
	justify-content: space-between;
}
.popular-button {
	display: flex;
	justify-content: center;
	margin-top: 36px;
}
/* top-artists */

.artist-list{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-row-gap: 30px;
}
.artist{
    display: flex;
    align-items: center;
}
.artist-img img{
	width: 60%;
}
 
.section-title{
    color: #562eff;
    font-size: 24px;
    padding: 30;
    margin-top: 3px;
}
.artist-name{
    margin-left: 16px;
    font-size: 18px;
}
.artist-content span {
	color: #FFAE00;
	font-weight: 600;
	text-transform: uppercase;
}
.artist-content h4 {
	text-transform: uppercase;
	font-weight: 400;
}
.top-artist{
    margin-bottom: 30px;
}
 .artist-title h5 {
	color: #333d45;
	text-transform: uppercase;
	font-size: 36px;
	font-weight: 400;
	text-align: center;
	margin-bottom: 22px;
}
/*footer*/
.footer-text p {
    padding-right: 14px;
}
.footer-icon a {
    font-size: 20px;
    color: #b8bcbf;
    margin-right: 25px;
    transition: .3s;
    margin-top: 25px;
    display: inline-block;
}
.footer-icon a:hover {
    color: #FFAE00;
}
.footer-widget h3 {
    font-size: 22px;
    margin-bottom: 47px;
    color: #FFAE00;
}
.footer-widget ul li a {
    font-size: 15px;
    color: #2B2929;
}
.footer-widget ul li {
    line-height: 1;
    margin-bottom: 20px;
}
.footer-menu ul li {
    display: inline-block;
    margin-right: 25px;
}
.footer-menu ul li a {
    color: #8d96a2;
    font-size: 13px;
}
.footer-menu ul li a:hover {
    color: #FFAE00;
}
.footer-widget ul li a:hover {
    color: #FFAE00;
}
/*copyright*/
 
.copyright-content p {
	padding: 10px 0;
	text-align: center;
	margin-bottom: 0;
	color: #fff;
}
