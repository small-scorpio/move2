# move2

box   : 元素id名

el    : 改变样式

timer : 运动时间

fn    : 回调函数

如：

move(box,
   {

        'height': 400,
        
        'width' : 300,
        
        'marginLeft' : 100
        
    },
    50,
    function () {
    
        move(
        
            box,
            {
            
                'height': 100,
                
                'width' : 100,
                
                'marginLeft' : 10
                
            },
            50
        )
    })
