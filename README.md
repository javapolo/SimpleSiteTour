���Ǹ��򵥵���ҳ���ܽ��ܵ��������ֻ����������ʹ��
this is a simple site tour plugin! it's easy to user,what you need to do is just two steps;

step one(��һ��):files depends on 
    
    <script src="weavertour/jquery_wev8.js"></script>
    <link rel="stylesheet" href="weavertour/weavertour.css">
    <script src="weavertour/weavertour.js"></script>

step two(�ڶ���):how to use it
     $(function(){
        
	 var config = {
	    steps:[
		     {title:"�������",describe:"������Ϣ",elid:"test",position:"right"},
		     {title:"�������1",describe:"������Ϣ1",elid:"test1",position:"top"},
		     {title:"�������2",describe:"<div color='red'>������Ϣ2</div>",elid:"test2",position:"left"},
		     {title:"�������3",describe:"������Ϣ3",elid:"test3",position:"left"}
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