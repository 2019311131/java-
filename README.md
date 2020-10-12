# java-
the java class

#阅读程序

##实验目的
用类描述计算机中的CPU速度以及磁盘的容量

##实验过程
利用Eclipse进行源代码的编译、调试及运行
用Github网站进行实验报告的撰写

概架设计，在Test主类下有CPU、HaroDisk，,PC三个分类，主类从分类调取参数并设计和调用显示函数show ()， 仓建项目Experiment,并创建包one。
创建CPU 1类，创建参数speed,并创建方法getSpeed。
创建HardDisk 1类，创建参数amonut,并创建方法getAmount。
创建PC类，创建属性cpu和HD,并创建方法getCPU、getHardDisk.为属性赋值，并创建显示函数show()↑在函数中利用打印函数对最终的cpu速度和硬盘容里进行显示.最后创建主类Test。

##核心方法
package pack;

 public class Text {
 public static void main(String args[]){
  
  CPU cpu =new CPU();
 
 class CPU {
  int speed;
  int getSpeed(){
   return speed;
  }
  public void setSpeed(int speed){
   this.speed=speed;
  }

 }
 
class HardDisk {
  int amount;
  int getAmount(){
   return amount;
  }
  public void setAmount(int amount){
   this.amount=amount;
  }

 }
 
 class PC {
  CPU cpu;
  HardDisk disk;
  void setCPU(CPU cpu){
   this.cpu=cpu;
  }
  void setHardDisk(HardDisk disk){
   this.disk=disk; 
  }
  
##实验感想
在此次JAVA实验中遇到了许许多多的困难，上次进行的实验测试，有些步骤已经忘记，通过请教同学以及观看b站视频一步一步的摸索了出来，在编写程序上也遇到了很大的阻力，不过在我和同学的共同努力下一起完成了它，接下来就是注册github账号以及上交内容，本来以为主体做完，这个应该不难了，没想到，这个想法是及其天真的，首先遇到的困难是保存的问题，网站提示搜索自己的文件，却怎么也搜不到，最后找到了JAVA的路径复制粘贴找到了地方，总之JAVA此次实验对我来说是个很大的挑战，通过此次JAVA实验，我又跟进了一步，这就是我的全部感悟

























