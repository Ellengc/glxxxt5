管理信息系统第六次作业
====================
查询test1看到的页面
------------------
![1i7c yx _n_1mp83f1l xx](https://cloud.githubusercontent.com/assets/16081097/19835219/528f05fa-9eba-11e6-9658-cd332787dd2b.png)
查询结果截图
-----------
![9d 3x 79y6zkg_2n 7p5](https://cloud.githubusercontent.com/assets/16081097/19835253/26924e20-9ebb-11e6-9d9a-69eba2140370.png)
伪代码
-----
1、根据用户名称查询UserID
2、根据用户ID查对应角色RoleIDs
3、权限表页面表并查找
   角色类型为CF_Role AND 角色编号在角色RoleIDs中
  OR
   角色类型为CF_User AND 人员编号为UserID
4、判断权限集合是否有查看权限输出对应页面
----------------
![8snm v8ejcst_f igxxxs1](https://cloud.githubusercontent.com/assets/16081097/19835254/2c0769d0-9ebb-11e6-82a6-02f73b84fe8e.png)
查询结果截图
-----------
![ger i 1k n u m2ltp 7aq](https://cloud.githubusercontent.com/assets/16081097/19835256/2f01494e-9ebb-11e6-8521-0e87d03c9267.png)
伪代码
------
1、根据名称查找人员编号UserID
2、根据人员编号UserID查找改人员所对应的角色RoleIDs
3、权限表按钮表页面表并查找
   角色类型为CF_Role AND 角色编号在角色RoleIDs中
  OR
    角色类型为CF_User AND 人员编号为UserID
4、  查询权限集合中菜单名为“订单”的数据据
