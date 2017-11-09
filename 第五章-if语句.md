# if语句

1. 是否相等（==）

   ```python
   >>>2==1+1 #1+1是否等于2
   True #是
   ```

2. 是否不等（!=）

   ```python
   >>>2!=1+1 #1+1是否不等于2
   False #否
   ```

3. 比较大小,and和or（>,  >=,  <...）

   ```python
   >>>8>2
   True
   >>>8>2 and 9<6
   False
   >>>8>2 or 9<6
   True
   ```

   ​

4. 检查特定值是否包含在列表中 

   ```python
   >>>A=[1,2,3]
   >>>9 in A #9是否在列表A中？
   False

   ```

   ​

5. 检查特定值是否不包含在列表中 

   ```python
   >>>A=[1,2,3]
   >>>9 in A #9是否不在列表A中？
   True
   ```

6. 判断list是否为空（元组、字符串、字典都可以如此判断）

   - **根据长度判断**

     长度为 0 的时候表示空

     ```python
     if len(list):
         pass      # this list is not None
     else:
         pass      # this list is None
     ```

     ​

   - **根据逻辑判断**

     空的 list 会返回 false

     ```python
     if list:
         pass      # this list is not None
     else:
         pass      # this list is None
     ```

     ​