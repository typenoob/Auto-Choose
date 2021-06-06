# Auto-Choose

浙江理工大学自动评教脚本，用于一键为优秀的老师投票

不负责任使用本脚本产生的后果与本人无关

### 使用步骤

1. 打开浏览器，进入评教页面，按`F12`，点击`Console`
2. 复制`Auto-Choose.js`内的全部内容，粘贴到`Console`里的“>”后
3. 修改`var choose = 5;`中的“5”来选择评哪个选项，数值1-5对应五个选项
4. 修改`var pingyu = "非常满意";`中的“非常满意”来修改需要填写的评语
5. 按下回车键，页面会自动跳转到最下方，点击提交（为了防止误提交此处没做成自动提交，需要手动确认）
6. 更换下一位教师，在`Console`的“>”后点击键盘的“上⬆️”方向键，重复步骤2～5
