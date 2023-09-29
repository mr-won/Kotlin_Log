# Kotlin_Log
Kotlin 데이터의 Log 찍는 법 정리, tag, simpleName 등
```
코드 최상단에 private val TAG = (플래그먼트나 액티비티이름)::class.java.simpleName 으로 선언하고
Log.d(TAG,dataModel.toString()) 이렇게 사용한다.

TAG를 선언해두면 Log를 찍어볼 때 편리하다.
```
