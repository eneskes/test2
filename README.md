# Test2
public class Test2{
static int count=0;
public void increment(){
count++;
}
public static void main(String[] args){
Test2 obj1=new Test2();
Test2 obj2=new Test2();
obj1.increment();
obj2.increment();
System.out.println(obj1.count);
System.out.println(obj2.count);
}}
