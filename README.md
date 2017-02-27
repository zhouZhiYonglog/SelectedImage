# SelectedImage
1.从系统图库选择图片或者照相机拍照获取图片的代码封装（默认UIAlertController形式，相册、相机、取消）导入该文件，一句话获取图片：
[[ZZYPhotoHelper shareHelper] showImageViewSelcteWithResultBlock:^(id data) {
        self.imageView.image = (UIImage *)data;
}];
2.如需自定义图片来源选项弹出视图，也可修改该文件，封装到文件里面，减少控制器代码量。
