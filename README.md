# The-javarice
// There are missing 8 cases in the Line 99 onwards the ide can't read the Twelve,Thirteen,Fourthteen,Fifteen,Sixteen,Seventeen,Eighteen, and 19 only the Eleven //


public static void main(String[] args) {
	      int numb;
	        Scanner in = new Scanner(System.in);

	        System.out.println("Enter Number: ");
	        numb = in.nextInt();

	        if (numb == 0) {

	            switch (numb) {
	                case 0:
	                    System.out.println("Zero");
	                    break;  
	            }
	                                if ((numb >= 10000 && numb <= 20000)){
	                                }
	                                
	                                    int thou = numb / 10000;
	                                    numb = numb % 10000;

	                                    switch (thou) {

	                                        case 1:
	                                            System.out.print("Ten Thousand ");
	                                            break;
	                                        case 2:
	                                            System.out.print("Eleven Thousand ");
	                                            break;
	                                        case 4:
	                                            System.out.print("Twelve Thousand ");
	                                            break;
	                                        case 5:
	                                            System.out.print("Thirteen Thousand ");
	                                            break;
	                                        case 6:
	                                            System.out.print("Fourteen Thousand ");
	                                            break;
	                                        case 7:
	                                            System.out.print("Fifteen Thousand ");
	                                            break;
	                                        case 8:
	                                            System.out.print("Sixteen Thousand ");
	                                            break;
	                                        case 9:
	                                            System.out.print("Seventeen Thousand ");
	                                            break;
	                                        case 10:
	                                            System.out.print("Eighteen Thousand ");
	                                            break;
	                                        case 11:
	                                            System.out.print("Nineteen Thousand ");
	                                            break;
	                                    }

	                                }

	                                if ((numb <= 1000) && (numb >= 9000)) {

	                                   int  thou = numb / 1000;
	                                    numb = numb % 9000;

	                                    switch (thou) {

	                                        case 1:
	                                            System.out.print("One Thousand ");
	                                            break;
	                                        case 2:
	                                            System.out.print("Two Thousand ");
	                                            break;
	                                        case 3:
	                                            System.out.print("Three Thousand ");
	                                            break;
	                                        case 4:
	                                            System.out.print("Four thousand");
	                                            break;
	                                        case 5:
	                                            System.out.print("five thousand");
	                                            break;
	                                        case 6:
	                                            System.out.print("six thousand");
	                                            break;
	                                        case 7:
	                                            System.out.print("seven thousand");
	                                            break;
	                                        case 8:
	                                            System.out.print("eight thousand");
	                                        case 9:
	                                            System.out.print("nine thousand");
	                                            break;
	                               
	                                    }

	                                }

	                                if ((numb <= 10) && (numb > 90)) {
	                                    int elevens = numb / 10;
	                                    numb = numb % 90;

	                                    switch (elevens) {

	                                        case 1:
	                                            System.out.print("ten ");
	                                            break;
	                                        case 2:
	                                            System.out.print("twenty ");
	                                            break;
	                                        case 3:
	                                            System.out.print("thirty ");
	                                            break;
	                                        case 4:
	                                            System.out.print("fourty ");
	                                            break;
	                                        case 5:
	                                            System.out.print("fifty ");
	                                            break;
	                                        case 6:
	                                            System.out.print("sixty ");
	                                            break;
	                                        case 7:
	                                            System.out.print("seventy ");
	                                            break;
	                                        case 8:
	                                            System.out.print("eighty ");
	                                            break;
	                                        case 9:
	                                            System.out.print("ninety ");
	                                            break;
	                                    }
	  
	                                }
	                                       
	                                         if((numb >=11) || (numb <19)){
	                                                int tens = numb / 11;
	                                                      numb = numb % 19;
	                              
	                                        switch (tens) {
	                                        case 1:
	                                            System.out.print("eleven ");
	                                            break;
	                                        case 2:
	                                            System.out.print("twelve ");
	                                            break;
	                                        case 3:
	                                            System.out.print("thirteen ");
	                                            break;
	                                        case 4:
	                                            System.out.print("fourteen ");
	                                            break;
	                                        case 5:
	                                            System.out.print("fifteen ");
	                                            break;
	                                        case 6:
	                                            System.out.print("sixteen ");
	                                            break;
	                                        case 7:
	                                            System.out.print("seventeen ");
	                                            break;
	                                        case 8:
	                                            System.out.print("eighteen ");
	                                            break;
	                                        case 9:
	                                            System.out.print("nineteen ");
	                                            break;
	                                            
	                                    }
	}
	                                
	                                    if ((numb <= 1) || (numb < 9)) {
	                                        int ones = numb / 1;
	                                        numb = numb % 9;
	                                        switch (ones) {

	                                            case 1:
	                                                System.out.print("one ");
	                                                break;
	                                            case 2:
	                                                System.out.print("two ");
	                                                break;
	                                            case 3:
	                                                System.out.print("three ");
	                                                break;
	                                            case 4:
	                                                System.out.print("four ");
	                                                break;
	                                            case 5:
	                                                System.out.print("five ");
	                                                break;
	                                            case 6:
	                                                System.out.print("six ");
	                                                break;
	                                            case 7:
	                                                System.out.print("seven ");
	                                                break;
	                                            case 8:
	                                                System.out.print("eight ");
	                                                break;
	                                            case 9:
	                                                System.out.print("nine ");
	                                                break;

	                                        }

	                                    }

	                                }
	}
