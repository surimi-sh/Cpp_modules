# CPP06_ex00

### **static_cast**
- 논리적으로 타입 변경이 가능한 경우만 변경을 허용한다.
- 포인터 타입을 정수 타입 등으로 변환하는 것은 방지해준다.
- 부모->자식, 자식->부모(위험하지만 허용) 모두 가능하다.
```cpp
	static_cast<type to cast>(variable to cast);
```