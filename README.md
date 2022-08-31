# Junit-automated-test
Junit在IntelliJ中进行测试

1 打开设置（ctrl+alt+s)，找到plugins；找到Junit Generator V2.0并安装
![image](https://user-images.githubusercontent.com/112142715/187587192-23b8bf4f-6fec-4784-bf7a-66980816dc20.png)

2 在编写的java文件中，生成构造器（Alt+Insert），导入 junit Test -> Junit 4

3 此时项目的src文件夹下出现test文件夹，并有前述java文件的Test文件；若此时@Test为红色，按导包修正快捷键（alt+enter），按提示将Junit4导入到工作路径
![image](https://user-images.githubusercontent.com/112142715/187587663-28ab10c5-758c-4f44-9208-bb3d2cb8abb0.png)

4 在Test文件的方法中编写代码，进行编译check是否通过
