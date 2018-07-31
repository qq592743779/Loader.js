# Loader.js <br>
资源预加载插件 <br>

使用方法：<br>
var loader = new Loader({<br>
    resources : [<br>
        'a.png','b.png','c.png' //  图片资源列表<br>
    ],<br>
    onStart : function(total){  //  资源总数<br>
    },<br>
    onProgress : function(current, total){  //  当前进度，总数<br>
    },<br>
    onComplete : function(total,totalTime){ //  总数，耗时（毫秒）<br>
    }<br>
});<br>
loader.start();<br>
