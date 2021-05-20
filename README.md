//class 1

public class Newclass {
	String name="Sai";
	void details()
	{
		System.out.println(name);
	}
}

//acessing class 1 from another class in same package

class Jala {
	public static void main(String[] args) {
		Newclass a = new Newclass();
		a.details();
	}
}
