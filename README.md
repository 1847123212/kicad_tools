# KiCAD�����ļ�������

ʹ�÷���:

1 ����mf_tool.py��"[KiCad��װĿ¼]\share\kicad\scripting\plugins" ·����

2 ��KiCAD��Python�����д����м�����������
```python
import mf_tool as mf
mf.GenMFDoc()
```
3 BOM�ļ���λ���ļ�����CSV��ʽ����ڵ�·����ͬĿ¼��

## ע��:

GenMFDoc() ��ı��·������ԭ�㡣��������GenMFDoc()����BOM�ļ���λ���ļ���������Gerber�ļ���

���ɵ�BOM�ļ��������ļ�����ֱ����sz-jlc.com������װ


# Manufacture Tools for kicad

Usage:

step 1: Copy the mf_tool.py to ��[kicad install path]\share\kicad\scripting\plugins��

step 2: In Python console window, type 
```python
import mf_tool as mf
mf.GenMFDoc()
```

step 3: the BOM and Postion CSV file will be generated under the same folder of the board file

## Attention:

The GenMFDoc() command will change the Aux original point