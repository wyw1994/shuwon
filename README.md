# shuwon
Yii2 文件上传组件
在共方法中添加actions
    'image' => [
        'class' => Action::className()
    ],
    'file' => [
        'class' => \shuwon\file\Action::className()
    ],
    'audio' => [
        'class' => \shuwon\audio\Action::className()
    ],
    'video' => [
        'class' => \shuwon\video\Action::className()
    ],
    