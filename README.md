���Ǹ��򵥵���ҳ���ܽ��ܵ��������ֻ����������ʹ��
this is a simple site tour plugin! it's easy to use,what you need to do is just two steps;

step one(��һ��):files depends on 
    
    <script src="weavertour/jquery_wev8.js"></script>
    <link rel="stylesheet" href="weavertour/weavertour.css">
    <script src="weavertour/weavertour.js"></script>

step two(�ڶ���):how to use it
     $(function(){
        
	 var config = {
	    steps:[
		     {title:"����һ",describe:"������Ϣ",elid:"test",position:"right"},
		     {title:"���ܶ�",describe:"������Ϣ1",elid:"test1",position:"top"},
		     {title:"������",describe:"<div color='red'>������Ϣ2</div>",elid:"test2",position:"left"},
		     {title:"������",describe:"������Ϣ3",elid:"test3",position:"left"}
		  ]
	}
	var WeaverTour = new WeaverTour(config);
	//��ʼ����
	WeaverTour.startTour();
      
     });

�������(�����ĸ�����������԰���html��ǩ)
    title ���ܱ���
    describe  ��������
    elid  Ԫ��id
    position  ��ͷ����