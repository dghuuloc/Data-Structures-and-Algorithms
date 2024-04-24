
## Solution
```java
public class Main {
	public static void alterString(String str1, String str2) {
		StringBuilder result = new StringBuilder();

		for (int index 0; index < str1.length() | index < str2.length(); index++) {
			if (index < str1.length()) {
				result.append(str1.charAt(index));
			}
			if (index < str2.length()) {
				result.append(str2.charAt(index));
			}
		}
		System.out.println(result);
	}
}
```
