# 时间别名

本类用于解决golang内置time输出json时格式问题
本类通过为time.Time创建别名，将内置的time格式化时的行为改变，并且不影响其自身与orm等组件类型映射功能的使用