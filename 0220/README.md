Execute

1. 수행결과로 Boolean 타입의 값을 반환합니다.

2. 모든 구문을 수행할 수 있습니다.

execute 함수를 사용하는 방법입니다.

  -> 리턴값이 ResultSet 일 경우에는 true, 이 외의 경우에는 false 로 출력됩니다.

  -> 리턴값이 ResultSet 이라고 하여 ResultSet 객체에 결과값을 담을 수 없습니다.


  ExecuteQuery

1. 수행결과로 ResultSet 객체의 값을 반환합니다.

2. SELECT 구문을 수행할 때 사용되는 함수입니다.


ExecuteUpdate

1. 수행결과로 Int 타입의 값을 반환합니다.

2. SELECT 구문을 제외한 다른 구문을 수행할 때 사용되는 함수입니다.

executeUpdate 함수를 사용하는 방법입니다.

 -> INSERT / DELETE / UPDATE 관련 구문에서는 반영된 레코드의 건수를 반환합니다.

 -> CREATE / DROP 관련 구문에서는 -1 을 반환합니다.
