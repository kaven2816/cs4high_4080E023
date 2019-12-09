# 利用Student做一個School的資料
public class School {
	private String OfficeName;//辦公室
	private String Numbering;//辦公室編號
	private String Extension;//分機號碼
	
	public School() {}
	
	public School(String O,String N,String E) {
		this.OfficeName=O;
		this.Numbering=N;
		this.Extension=E;
	}
	
	public void printfSchool(){
		System.out.println("辦公室名稱："+OfficeName+"辦公室編號："+Numbering+"分機號碼："+Extension);
	}
	
	public static void main(String[]args) {
		School obj_s1 = new School("校長室","001","-001");
		obj_s1.printfSchool();
		School obj_s2 = new School("學務處","002","-002");
		obj_s2.printfSchool();	
	}
}

```
