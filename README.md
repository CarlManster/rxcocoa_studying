# rxcocoa_studying
rxcocoa_studying

# Scheduler
http://minsone.github.io/programming/reactive-swift-observeon-subscribeon
멀티스레드를 사용하여 여러가지 작업을 Observable 연산자로 묶어 수행하는 경우가 있습니다. 가령 백그라운드 스레드에서는 네트워크 작업, 많은 연산이 필요한 작업을 해야하고, 화면에 보여주기 위해서는 메인 스레드에서 작업을 해야합니다.
이 작업들은 Observable 연산자로 묶어 만들 수 있으므로, 각각의 작업에 맞게 스레드 지정을 해야합니다.
Scheduler는 스레드를 가르키는 말입니다.

## observeOn
Observable이 Observer에게 알리는 스케줄러를 지정

## subscribeOn
Observable이 동작하는 스케줄러를 지정

# Driver
http://minsone.github.io/programming/reactive-swift-observable-vs-driver
Driver는 UI layer에서 좀 더 직관적으로 사용하도록 제공하는 unit입니다. Observable는 상황에 따라 MainScheduler와 BackgroundScheduler를 지정해줘야 하지만 Driver는 MainScheduler에서 사용합니다.

