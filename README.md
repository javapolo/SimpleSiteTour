这是个简单的网页功能介绍导航插件，只需两步即可使用
this is a simple site tour plugin! it's easy to use,what you need to do is just two steps;

step one(第一步):files depends on 
    
    <script src="weavertour/jquery_wev8.js"></script>
    <link rel="stylesheet" href="weavertour/weavertour.css">
    <script src="weavertour/weavertour.js"></script>

step two(第二步):how to use it
     $(function(){
        
	 var config = {
	    steps:[
		     {title:"功能一",describe:"描述信息",elid:"test",position:"right"},
		     {title:"功能二",describe:"描述信息1",elid:"test1",position:"top"},
		     {title:"功能三",describe:"<div color='red'>描述信息2</div>",elid:"test2",position:"left"},
		     {title:"功能四",describe:"描述信息3",elid:"test3",position:"left"}
		  ]
	}
	var WeaverTour = new WeaverTour(config);
	//开始导航
	WeaverTour.startTour();
      
     });

参数简介(以下四个参数里面可以包含html标签)
    title 功能标题
    describe  功能描述
    elid  元素id
    position  箭头方向