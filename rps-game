import java.util.*;
class Rps{

    public static void main(String[] args){
    String user;
    Scanner sc = new Scanner(System.in);

    System.out.println("Enter r p or s");
    user = sc.nextLine();
    
    String[] rps = {"r", "p", "q"};
    String compMove = rps[new Random().nextInt(rps.length)];

    System.out.println("Computer Moved :" + compMove);

    Winner w = new Winner();

     w.whoWon(user, compMove);
  
    }
}

class Winner{

    void whoWon(String user, String compMove){
     if(user.equals("r") && compMove.equals("s") || user.equals("p") && compMove.equals("r") || user.equals("s") && compMove.equals("p"))
     {
        System.out.println("You Win!");
     }
     else if (user.equals("r") && compMove.equals("p") || user.equals("p") && compMove.equals("s") || user.equals("s") && compMove.equals("r")){
        System.out.println("You Lose");
     }
     else{
        System.out.println("Its a Tie");
     }
    }
}
