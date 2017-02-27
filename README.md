# SelectedImage
从系统图库选择图片或者照相机拍照获取图片的代码封装（UIAlertController形式，相册、相机、取消）导入该文件，一句话获取图片：
[[ZZYPhotoHelper shareHelper] showImageViewSelcteWithResultBlock:^(id data) {
        self.imageView.image = (UIImage *)data;
}];
