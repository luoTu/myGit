# myGit
学习
...java

public class SingletonHungry {
    //注意这里使用了final关键字
	private static final SingletonHungry singleton=new SingletonHungry();
	    
	private SingletonHungry() {
 
	}
	
	public static SingletonHungry GetInstance() {
		
		return singleton;
		
	}
