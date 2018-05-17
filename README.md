# VisionPro_Script_ToolGroup
How to coding for visionpro script 
#当使用visionpro脚本时踩过的几个坑：
#1.使用你在toolGroup里面的工具时正确写法应该是：
CogPMAlignTool myTool = new CogPMAlign();
myTool = (CogPMAlignTool)toolGroup.Tools["CogPMAlignTool1"];
