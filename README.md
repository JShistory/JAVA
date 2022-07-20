# 자바 문법 정리
String 관련 메소드

String str = "abcde";
str.length() // str의 길이 반환
str.isEmpty() // str의 길이가 0이면 true, 아니면 false
str.charAt(2) // 인덱스로 문자 찾기, c 반환
str.indexOf("c") // 문자로 첫번째 인덱스 찾기, 2 반환
str.lastIndexOf("c") // 문자의 마지막 인덱스 찾기, 2 반환
str.substring(2, 4) // 2~3 위치의 문자열 "cd" 반환
str.substring(3) // 3부터 끝까지의 문자열 "de" 반환
str.replace('b', 'k') // b를 k로 변경 (akcde)
str.equals("abcde") // str과 abcde를 비교해서 같으면 true, 다르면 false
str.contains("bc") // str에 bc가 포함되어 있으면 true, 아니면 false
str.split(" ") // 띄어쓰기로 구분된 문자열 str을 분리해서 String[] 배열 반환
str.split() // 띄어쓰기 없는 문자열 str을 한 문자씩 분리해서 String[] 배열 반환
str.trim() // str의 앞뒤 공백 제거, 문자열 사이 공백은 제거 X
str.toLowerCase() // 대문자를 모두 소문자로 변경
str.toUpperCase() // 소문자를 모두 대문자로 변경
str.compareTo("abcdd")
/*
str과 abcdd가 같으면 0
str이 abcdd보다 사전순으로 앞이면 -1
str이 abcdd보다 사전순으로 뒤면 1
str과 abcdd가 마지막 문자만 다르면 마지막 문자의 사전순 차이 반환 (여기선 1)
*/
Integer.parseInt("300") // 문자열을 숫자로 변환
Integer.toString(300) // 숫자를 문자열로 변환
