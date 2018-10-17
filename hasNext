# hasNext
import java.util.Scanner;
import java.util.HashSet;
import java.util.Iterator;
import java.util.Set;

public class hasNext {
	public static void main(String args[]) {
		 Set<String> setTest = new HashSet<String>();
		 int i;
		 /* 
          * 宣告Iterator型態的變數 it，
          * 限制只能將String型態加入it 
          */ 
         Iterator it;
          
         
         String[] x={"a","b","c"};
        
         
         
         for( i=0;i<x.length;i++){
        	 setTest.add(x[i]);//可運用line b o t 把迴圈拿掉 ex setTest.add(x[i]); i++;
         }
         
         it = setTest.iterator(); 
         /*
          * hasNext()為使用游標走訪Iterator物件，檢查下一筆元素是包含物件，
          * 有包含物件則傳回true，否則false。
          * 游標的起始位置在Iterator第一筆元素之前，所以第一次執行hasNext()，
          * 會檢查Iterator的第一筆元素，使用此方式可以走訪Iterator內的所有物件
          */
          while (it.hasNext()) {   
         /*
          * next()為使用游標走訪Iterator，取出下一筆的值。
          * 游標的起始位置在Iterator第一筆之前，所以第一次執行next()，會
          * 取出Iterator的第一筆資料
          */
          System.out.println(it.next());
          
          
		
		}
		
	}
	}

