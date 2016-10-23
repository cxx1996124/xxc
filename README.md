#一、用例图
![text](https://github.com/cxx1996124/xxc/blob/master/2.png)
#二、用例说明
<table width="800" border="1">
<tr>
	<td>用例名称</td>
	<td>设备检修</td>
	<td rowspan="2">用例类型：业务需求						
	</td>
</tr>
<tr>
	<td>主要业务参与者</td>	
	<td>设备保养员</td>	
</tr>
<tr>
	<td>其他参与者</td>	
	<td>设备维修员 管理员</td>
</tr>
<tr>
	<td>描述</td>
	<td>该用例描述了一个设备检修系统。保养员对到期的设备进行检修，并做记录。当发现设备故障时，维修员对其进行维修并记录其耗材。同时管理员可以查询设备信息</td>
</tr>
<tr>
	<td rowspan="2">典型事件过程</td>	
	<td>参与者动作</td>	
	<td>系统响应</td>
</tr>
<tr>
	<td>第一步：输入设备编号</td>
	<td>第二步：系统自动查询其检修类型等信息
	第三步：在对应的设备保养单上填写保养记录	
	第四步：提交保养单，完成保养</td>	
</tr>
<tr>
	<td>替代事件过程</td>	
	<td>替代第四步：如果设备故障，则对其进行维修，并记录维修耗材，填写维修记录单。</td>	
</tr>
	<td>结论</td>	
	<td>设备状态正常时，完成设备保养。</td>	
</table>
