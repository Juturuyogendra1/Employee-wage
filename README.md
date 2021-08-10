public class uc1 {

        public static void main(String[] args) {
            int  ISFULLTIME = 1;
            System.out.println("progress to check Employee is present or absent");
            System.out.println("calculate  daily Employee wage");
            double emp_check = Math.floor((Math.random() * 10) % 2);
            int perhour = 2;
            int totalhours = 8;
            int parttimehour= 5 ;
            int salaryperhour = 3;
            int  dailywage = 8;
         if   ( emp_check == ISFULLTIME) {
                System.out.println("Employee IS present");
                System.out.println((totalhours * salaryperhour));
                System.out.println(parttimehour);
                System.out.println("daily wage =20");
            }
         else
            System.out.println("Employee is absent");

        }
    }
