
# JAVA 8 Features
--------
## Description2

	import java.util.*;  
	class Product{  
    int id;  
    String name;  
    float price;  
    public Product(int id, String name, float price) {  
        this.id = id;  
        this.name = name;  
        this.price = price;  
    }  
    public String toString()
    {
        return id+" "+name+" "+" "+price;
    }
	}  
	public class JavaStreamExample {  
    public static void main(String[] args) {  
        List<Product> productsList = new ArrayList<Product>();  
        //Adding Products  
        productsList.add(new Product(1,"HP Laptop",25000f));  
        productsList.add(new Product(2,"Dell Laptop",30000f));  
        productsList.add(new Product(3,"Lenevo Laptop",28000f));  
        productsList.add(new Product(4,"Sony Laptop",28000f));  
        productsList.add(new Product(5,"Apple Laptop",90000f));  
        productsList.stream()  
                    .filter(p1 ->p1.id< 3)      // filtering price  
                    .map(pm1 ->pm1.id)   
                   // .map(pm2->pm2.name)           // fetching price  
                    .forEach(System.out::println);  // iterating price  */
                    productsList.forEach(System.out::println);
   	 }  
	} 
