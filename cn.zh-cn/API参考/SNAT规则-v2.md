# SNAT规则 v2<a name="nat_api_0030"></a>

<a name="table1351682493510"></a>
<table><thead align="left"><tr id="row1759512463518"><th class="cellrowborder" valign="top" width="26%" id="mcps1.1.5.1.1"><p id="p3595424163511"><a name="p3595424163511"></a><a name="p3595424163511"></a>API</p>
</th>
<th class="cellrowborder" valign="top" width="14.44%" id="mcps1.1.5.1.2"><p id="p19512155317473"><a name="p19512155317473"></a><a name="p19512155317473"></a>API功能</p>
</th>
<th class="cellrowborder" valign="top" width="16.75%" id="mcps1.1.5.1.3"><p id="p19595172413511"><a name="p19595172413511"></a><a name="p19595172413511"></a>授权项</p>
</th>
<th class="cellrowborder" valign="top" width="42.809999999999995%" id="mcps1.1.5.1.4"><p id="p1366363695811"><a name="p1366363695811"></a><a name="p1366363695811"></a>授权项作用域</p>
</th>
</tr>
</thead>
<tbody><tr id="row15595192412355"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.1 "><p id="p11212134219518"><a name="p11212134219518"></a><a name="p11212134219518"></a>POST /v2/{project_id}/snat_rules</p>
</td>
<td class="cellrowborder" valign="top" width="14.44%" headers="mcps1.1.5.1.2 "><p id="p18200102818515"><a name="p18200102818515"></a><a name="p18200102818515"></a>创建SNAT规则</p>
</td>
<td class="cellrowborder" valign="top" width="16.75%" headers="mcps1.1.5.1.3 "><p id="p9200928135113"><a name="p9200928135113"></a><a name="p9200928135113"></a>nat:snatRules:create</p>
</td>
<td class="cellrowborder" valign="top" width="42.809999999999995%" headers="mcps1.1.5.1.4 "><a name="ul5542718184316"></a><a name="ul5542718184316"></a><ul id="ul5542718184316"><li>支持：<a name="ul85758552477"></a><a name="ul85758552477"></a><ul id="ul85758552477"><li>项目 （Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li><li>不支持：无</li></ul>
</td>
</tr>
<tr id="row959782416351"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.1 "><p id="p821214215118"><a name="p821214215118"></a><a name="p821214215118"></a>GET /v2/{project_id}/snat_rules</p>
</td>
<td class="cellrowborder" valign="top" width="14.44%" headers="mcps1.1.5.1.2 "><p id="p320012810516"><a name="p320012810516"></a><a name="p320012810516"></a>查询SNAT规则列表</p>
</td>
<td class="cellrowborder" valign="top" width="16.75%" headers="mcps1.1.5.1.3 "><p id="p102002281512"><a name="p102002281512"></a><a name="p102002281512"></a>nat:snatRules:list</p>
</td>
<td class="cellrowborder" valign="top" width="42.809999999999995%" headers="mcps1.1.5.1.4 "><a name="ul139841920114910"></a><a name="ul139841920114910"></a><ul id="ul139841920114910"><li>支持：<a name="ul7984132054916"></a><a name="ul7984132054916"></a><ul id="ul7984132054916"><li>项目 （Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li><li>不支持：无</li></ul>
</td>
</tr>
<tr id="row459717246353"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.1 "><p id="p321224215512"><a name="p321224215512"></a><a name="p321224215512"></a>GET /v2/{project_id}/snat_rules/{snat_rule_id }</p>
</td>
<td class="cellrowborder" valign="top" width="14.44%" headers="mcps1.1.5.1.2 "><p id="p3200132813513"><a name="p3200132813513"></a><a name="p3200132813513"></a>查询SNAT规则详情</p>
</td>
<td class="cellrowborder" valign="top" width="16.75%" headers="mcps1.1.5.1.3 "><p id="p1920019289511"><a name="p1920019289511"></a><a name="p1920019289511"></a>nat:snatRules:get</p>
</td>
<td class="cellrowborder" valign="top" width="42.809999999999995%" headers="mcps1.1.5.1.4 "><a name="ul1899012201498"></a><a name="ul1899012201498"></a><ul id="ul1899012201498"><li>支持：<a name="ul1599012054911"></a><a name="ul1599012054911"></a><ul id="ul1599012054911"><li>项目 （Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li><li>不支持：无</li></ul>
</td>
</tr>
<tr id="row1159792493517"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.1 "><p id="p02132421515"><a name="p02132421515"></a><a name="p02132421515"></a>DELETE /v2/{project_id}/snat_rules/{snat_rule_id}</p>
</td>
<td class="cellrowborder" valign="top" width="14.44%" headers="mcps1.1.5.1.2 "><p id="p17200192835117"><a name="p17200192835117"></a><a name="p17200192835117"></a>删除SNAT规则</p>
</td>
<td class="cellrowborder" valign="top" width="16.75%" headers="mcps1.1.5.1.3 "><p id="p220062819517"><a name="p220062819517"></a><a name="p220062819517"></a>nat:snatRules:delete</p>
</td>
<td class="cellrowborder" valign="top" width="42.809999999999995%" headers="mcps1.1.5.1.4 "><a name="ul599742024914"></a><a name="ul599742024914"></a><ul id="ul599742024914"><li>支持：<a name="ul1199782064914"></a><a name="ul1199782064914"></a><ul id="ul1199782064914"><li>项目 （Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li><li>不支持：无</li></ul>
</td>
</tr>
<tr id="row85979249353"><td class="cellrowborder" valign="top" width="26%" headers="mcps1.1.5.1.1 "><p id="p1213742185114"><a name="p1213742185114"></a><a name="p1213742185114"></a>PUT /v2/{project_id}/snat_rules/{snat_rule_id}</p>
</td>
<td class="cellrowborder" valign="top" width="14.44%" headers="mcps1.1.5.1.2 "><p id="p20200112816513"><a name="p20200112816513"></a><a name="p20200112816513"></a>更新SNAT规则</p>
</td>
<td class="cellrowborder" valign="top" width="16.75%" headers="mcps1.1.5.1.3 "><p id="p3200028125112"><a name="p3200028125112"></a><a name="p3200028125112"></a>nat:snatRules:update</p>
</td>
<td class="cellrowborder" valign="top" width="42.809999999999995%" headers="mcps1.1.5.1.4 "><a name="ul19352114492"></a><a name="ul19352114492"></a><ul id="ul19352114492"><li>支持：<a name="ul4392112492"></a><a name="ul4392112492"></a><ul id="ul4392112492"><li>项目 （Project）</li><li>企业项目（Enterprise Project）</li></ul>
</li><li>不支持：无</li></ul>
</td>
</tr>
</tbody>
</table>

