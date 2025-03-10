# Producer_consumer_problem

-Object.wait()를 사용해 소비자와 생산자가 대기시 락을 반납하고 대기(waiting)하도록 바꿨습니다.

-Object.notify()를 사용해 객체자체에 가지고 있는 대기집합에서 스레드를 하나 깨우도록 하였습니다.

-소비자가 소비를 하거나 생산자가 생산을 할시 notify()를 호출하여 스레드가 대기시 이를 runnable상태로 바꿔주도록 하였습니다.

<br>

*결과에는 문제 없지만 notify()를 사용시 생산자가 소비자가 아닌 또 생산자를 깨우는 일부 비효율이 발생한다.->Object.notify()은 한계
