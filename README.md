/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

package squares;
import java.util.*;

/**
 *
 * @author RaCoc9605
 */
public class Squares {
    
    
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        ArrayList <Integer> squares = new ArrayList();
        Collections.addAll(squares, 0 , 1 , 4 , 9 , 16 , 25 , 36 , 49 , 64 , 81);
        
        System.out.println("Squares\n**************\n");
        for (int i = 0; i < squares.size(); i++)
        {
            System.out.println("Numbers: " + i + " Squared: " + squares.get(i));
            
        }
        

    }
    
}
