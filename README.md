# python-utf-8-
#汉字转utf-8
import sys
reload(sys)
sys.setdefaultencoding('utf-8')
u = u'王冉王叔叔'.encode('utf-8')
u

#utf-8转汉字
u = '\xe7\x8e\x8b\xe5\x86\x89\xe7\x8e\x8b\xe5\x8f\x94\xe5\x8f\x94'.decode('gbk')
print u
