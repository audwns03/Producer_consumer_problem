# Producer_consumer_problem

-Version3의 비효율을 해결하기 위한 대기집합분리의 사전작업을 진행하였습니다.

-오브젝트 객체에 있는 락을 사용하는 대신 ReentrantLock을 사용하도록 바꿨습니다.

-오브젝트 객체에 있는 스레드 대기 공간이 아닌 ReentrantLock의 스레드 대기 공간인 Condition을 사용하도록 바꿨습니다.
