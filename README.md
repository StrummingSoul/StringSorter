# StringSorter
StringSorter
import java.util.Arrays;

public class StringSorter {
    public static void main(String[] args) {
        String input = "openai";
        String sortedString = sortString(input);
        System.out.println("Отсортированная строка: " + sortedString);
    }

    public static String sortString(String input) {
        char[] chars = input.toCharArray();
        Arrays.sort(chars);
        return new String(chars);
    }
}
