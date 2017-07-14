# display hidden显示与隐藏
# 代码
    $(document).on("click",function(){//对document绑定一个影藏Div方法
        $(".userinfo").addClass("userinfos");
        $(".menu").addClass("menus");
    });
    functionshow_scenic(e){
        if(e.stopPropagation)
            e.stopPropagation();
        else
            e.cancelBubble=true;
    };

点击该元素时，显示隐藏，点击其他位置，隐藏

