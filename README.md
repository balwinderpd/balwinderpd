@import url('https://fonts.googleapis.com/css2?family=Baloo+Bhaina+2&display=swap');
body{
	font-family: 'baloo bhaina 2', cursive;
	background-color: #eee;
}

.container-fluid{
	
	width: 40%;
	margin: 0 auto;
	margin-top: 100px;	
}

.container-fluid h2{
	
	color: hotpink;
	position: relative;
	width: 23rem;
}

.container-fluid h2::after{
	content: "";
	position: absolute;
	bottom: 0;
	right: 22px;
	width: 67px;
	height: 2px;
	background-color: hotpink;
}

.accordion{
	width: 100%;
	padding: 0 5px;
	border: 2px solid #6db5ff;
	cursor: pointer;
	border-radius: 50px;
	display: flex;
	margin: 10px 0;
	align-items: center;
}

.accordion .icon{
	margin: 0 10px 0 0;
	width: 30px;
	height: 30px;
	background: url("images/3.png") no-repeat 2px 3px #6db5ff;
	border-radius: 50%;
	float: left;
	transition: all .5s ease-in;
}

.accordion h5{
	font-size: 22px;
	margin: 0;
	padding: 3px 0 0 0;
	font-weight: normal;
	color: #1f5c9a;
}

.active .icon{
	background: url("file:///C:/Users/DEEL/Downloads/dr%20-%20Copy/images/2.png")no-repeat 2px 3px #fff;
}

.active{
	background-color: #6db5ff;
	color: #fff;
}

.active h5{
	color: #fff;
}

.panel{
	padding: 0 15px;
	border-left: 1px solid #6db5ff;
	margin-left: 25px;
	font-size: 14px;
	text-align: justify;
	overflow: hidden;
	max-height: 0px;
	transition: all .5s ease-in;
}

.imgg{
	float: right;
	height: 100px;
	width: 100px;
	margin-left: 80px;
}



