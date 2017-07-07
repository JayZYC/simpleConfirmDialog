# simpleConfirmDialog
参考大神写的，自己改的简单的显示提示信息的dialog

使用示例：
  new DialogConfirm(mContext)
                        .setTitle("这是标题")
                        .setText("这是提示信息")
                        .setCancelable(false)
                        .setButton("这是右侧按钮")
                        .noLeftButton()
                        .rightOnClickButton(new View.OnClickListener() {
                            @Override
                            public void onClick(View v) {
                                //这里写右侧按钮点击事件
                            }
                        })
                        .setButtonColor(mContext.getResources().getColor(R.color.blue))
                        .DialogConfirm()
                        .show();
