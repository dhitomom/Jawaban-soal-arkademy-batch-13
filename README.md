# Jawaban-soal-arkademy-batch-13
Jawaban no.4

```
import java.util.Scanner;
public class Main {
  public static void main(String[] args) {

    Scanner scanner = new Scanner(System.in);
    String input = scanner.nextLine();
    String[]printWords = input.split("");
    for (int i = 0; i < printWords.length; i++) {
      if(printWords[i].equalsIgnoreCase("A")||printWords[i].equalsIgnoreCase("I")||printWords[i].equalsIgnoreCase("U")||printWords[i].equalsIgnoreCase("E")||printWords[i].equalsIgnoreCase("O"))
      {
        System.out.println(printWords[i]);
    }
  }
    for (int i = 0; i < printWords.length; i++) {
      if(!printWords[i].equalsIgnoreCase("A")&&!printWords[i].equalsIgnoreCase("I")&&!printWords[i].equalsIgnoreCase("U")&&!printWords[i].equalsIgnoreCase("E")&&!printWords[i].equalsIgnoreCase("O"))
      {
        System.out.println(printWords[i]);
    }
  }
  }
}
```
