
# JAVA 8 Features
--------
## Description

	package myproject;
	import java.util.stream.Collectors;
	import java.util.stream.Stream;
	// w  w w .j  a va2  s .com
	public class CollectAverage {
 	public static void main(String[] args) {
    Stream<String> s = Stream.of("1","2","3");
    
    double o =  s.collect(Collectors.averagingDouble(n->Double.parseDouble(n)));

    System.out.println(o);
  	}
	}
