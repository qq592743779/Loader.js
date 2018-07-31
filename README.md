# Loader.js
资源预加载插件

使用方法：
var loader = new Loader({
    resources : [
        'a.png','b.png','c.png' //  图片资源列表
    ],
    onStart : function(total){  //  资源总数
    },
    onProgress : function(current, total){  //  当前进度，总数
    },
    onComplete : function(total,totalTime){ //  总数，耗时（毫秒）
    }
});
loader.start();
