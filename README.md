
拷贝属性
//        copy object properties
BeanUtils.copyProperties(employeeDTO, employee);

ThreadLocal 为每个线程单独一份存储空间，具有线程隔离的效果，只有在线程内才能获取到对应的值，线程外则不能访问。

通过ThreadLocal 存储用户信息等，避免参数传递的麻烦。