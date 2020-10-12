# java-
the java class

#阅读程序

##实验目的
用类描述计算机中的CPU速度以及磁盘的容量

##实验过程
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
  


##实验结果














##实验感想









