1. 관계형 데이터베이스(RDBMS)와 비관계형 데이터베이스(NoSQL)의 장단점 비교
관계형 데이터베이스는 각 테이블 간의 PK, FK, Unique Key 등 서로 스키마 간의 관계를 고려해서 만드는 데이터베이스를 관계형 데이터베이스라고 한다. 서로 간의 연결성을 생각해 조인을 하여 데이터를 조회할 수 있다.
비관계형 데이터베이스는 말 그대로 테이블 간의 관계성 없이 만든 스키마를 말한다. 컬럼이 무한대로 많아질 수 있고 빅데이터처리 시 유리하다.

관계형 데이터베이스는 빅데이터처리에 있어서 용이하지 않지만 정보계 마트 생성 시 유리하다. 하지만 비관계형 데이터베이스는 컬럼을 추가하여 대용량의 데이터를 처리할 수 있는 장점이 있다. 유니크한 메타키값이 있지만 중복이 허용된다.

2. 트랜잭션(transaction)이란 무엇인가요?

ACID 속성에 따라 하나의 처리에 있어 해당 사항이 충족되지 않을 경우, ROLLBACK이 되고 충족이 되면 COMMIT된다.

3. MySQL에서 조인(join)의 역할은 무엇인가요? 다양한 join의 방식에 대해 설명해주세요.

여러 테이블을 서로의 관계성에 따라 Key값으로 조인하여 하나의 테이블에서 가져올 수 없는 정보를 다른 테이블을 참조하여 끌어오는 것을 말한다.
INNER JOIN, OUTER JOIN, LEFT/RIGHT JOIN 등 여러 방식의 조인이 있다.

4. MySQL에서 인덱스(index)란 무엇인가요?

인덱스는 데이터를 조회할 때 조회속도를 높혀줄 수 있게 인덱스를 설정하는 것을 말한다.
하나의 조회성능을 높이는 키라고 말할 수 있다.
