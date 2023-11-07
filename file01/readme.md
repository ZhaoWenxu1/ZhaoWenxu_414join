#414面试


##自我介绍


我是数字媒体技术2班的赵文绪，我做事认真负责，不怕困难也善于解决困难。我对该专业有很大的兴趣，希望我能有机会成为部门的一份子。


##加入414后


-我想学习与该专业相关的各种软件的技能并且可以熟练使用，比如AE,MAYA,C4D等


-我想通过该社团与同学合作参加专业比赛


-我想通过该社团提升专业水平

##图片

！[linear](file01/Howl's-Moving-Castle-Studio-Ghibli-fantasy-art-clouds-daylight-couple-1745785-wallhere.com.jpg)


##冒泡算法

###冒泡算法过程

•比较相邻的元素。如果第一个比第二个大（升序），就交换他们两个。

•对每一对相邻元素作同样的工作，从开始第一对到结尾的最后一对。这步做完后，最后的元素会是最大的数。

•针对所有的元素重复以上的步骤，除了最后一个

•持续每次对越来越少的元素重复上面的步骤，直到没有任何一对数字需要比较。

###伪代码

def bubble_sort(alist):

for j in range (len(alist)-1,0,-1)：

＃ j表示每次通历需要比较的次数，是逐渐诚小的

for i in range(j):

if alist[i] > alist[i+1]:

alist[il, alist[i+1] = alist[i+1], alist[i]

li = [54, 26, 93, 17, 77, 31,44, 55,20]

bubble_sort(li)

print (li)

