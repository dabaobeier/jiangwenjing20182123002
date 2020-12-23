# jiangwenjing20182123002
5.什么是依赖？它与关联有什么区别？
答：依赖是一种使用关系，它说明了一个事物声明说明的变化可能影响到使用它的另一个事物，但反之未必。也就是说，服务的使用者以某种方式依赖于服务的提供者。而关联是一种结构关系，它详述了一个事物的对象与另一个事物的对象相互联系。

6.什么是泛化？泛化是否就是类的继承，如果不是请说明理由。
答：泛化是一般事物(称为父类或超类)和较特殊事物(称为子类或孩子类)之间的关系。泛化不是类的继承，类的继承是泛化的一种。

（2）
2.学期筛选类：
属性	    全部数据	                  18至20学年所有成绩
	      18至19学年上学期      	显示该学期内的所有成绩，类型为String，Private属性
	      18至19学年下学期	      显示该学期内的所有成绩，类型为String，Private属性
	      19至20学年上学期	      显示该学期内的所有成绩，类型为String，Private属性
	      19至20学年下学期      	显示该学期内的所有成绩，类型为String，Private属性

方法	      查询	              查询在该学期内的所有成绩信息
	          打印               	打印该学期内的所有成绩信息
            
成绩下载类：
属性	    姓名	                类型为String，Private属性
	        学号	                类型为int，Private属性
	        学院	                类型为String，Private属性
         	班级	                类型为String，Private属性
	        学期	                成绩所属学期，类型为String，Private属性
	        课程名称	            类型为String，Private属性
	        课程性质	            类型为String，Private属性
	        成绩类型	            成绩类型为期末总评，类型为String，Private属性
	        应修学分	            该课程应修学分，类型为String，Private属性
	        实修学分	            该课程实际所修学分，类型为String，Private属性
	        成绩	                该课程的成绩，类型为String，Private属性
	        绩点	                该课程成绩绩点，类型为String，Private属性
	        学分绩	               该课程学分绩，类型为String，Private属性
方法	    保存	                保存所有成绩
	        发送	                发送成绩表
成绩下载类：
属性	    姓名	                类型为String，Private属性
	        学号	                类型为int，Private属性
	        学院	                类型为String，Private属性
	        班级	                类型为String，Private属性
	        学期	                成绩所属学期，类型为String，Private属性
	        课程名                类型为String，Private属性
	        课程性质	            类型为String，Private属性
	        成绩类型	            成绩类型为期末总评，类型为String，Private属性
	        应修学分	            该课程应修学分，类型为String，Private属性
	        实修学分	            该课程实际所修学分，类型为String，Private属性
	        成绩	                该课程的成绩，类型为String，Private属性
	        绩点	                该课程成绩绩点，类型为String，Private属性
	        学分绩	               该课程学分绩，类型为String，Private属性
方法	    保存	                保存所有成绩
	        发送	                发送成绩表

成绩类
属性	    考试科目	             类型为String，Private属性
		      总评成绩	             类型为String，Private属性
			    总评成绩	             类型为String，Private属性
			    学期	                 类型为String，Private属性
			    学科类型	             类型为String，Private属性
			    应修学分	             类型为String，Private属性
			    实修学分	             类型为String，Private属性
			    绩点	                 类型为String，Private属性
			    学分绩	                类型为String，Private属性
			    平时成绩	             类型为Int，Private属性
			    作业成绩	             类型为Int，Private属性
			     期中成绩	             类型为Int，Private属性
			     期末成绩	             类型为Int，Private属性
3.类之间分别有什么关系
成绩类和成绩下载类是依赖关系，成绩下载类和学期筛选类是普通关联，学期筛选类和成绩类是依赖关系。





