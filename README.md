# scriptcn

����һ���µ�repository


cd ~/scriptcn

git init

git add .

git commit

git remote add https://github.com/scriptcn/scriptcn.github.io.git

git push origin master

2.������Ŀ���¼����ļ�����
 
$cd ~/hello-world
 
$git add . //���������Զ��ж��¼�����Щ�ļ��������ֶ������ļ�����
 
$git commit //�ύ�����زֿ�
 
$git push origin master //�����´����ģ�������add ��remote����
 
3.������Ŀ��û�¼��ļ���ֻ��ɾ�������޸��ļ�����
 
$cd ~/hello-world
 
$git commit -a //��¼ɾ�����޸�����Щ�ļ�
 
$git push origin master //�ύ��github
 
4.����һЩ�ļ�������*.o��:
 
$cd ~/hello-world
 
$vim .gitignore //���ļ����ͼ��뵽.gitignore�У�����
 
Ȼ��Ϳ���git add . ���Զ����������ļ�
 
5.clone���뵽���أ�
 
$git clone https://github.com/scriptcn/scriptcn.github.io.git
 
���籾���Ѿ������˴��룬���ֿ����и��£��Ѹ��ĵĺϲ������ص���Ŀ��
 
$git fetch origin //��ȡԶ�̸���
 
$git merge origin/master //�Ѹ��µ����ݺϲ������ط�֧
 
6.����
 
$git reset
 
7.ɾ��
 
$git rm * // ������rm
 
//���������������������������󡪡��������������������C
 
1.$ git remote add origin https://github.com/scriptcn/scriptcn.github.io.git
 
������ʾ��fatal: remote origin already exists.
 
����취��$ git remote rm origin
 
Ȼ����ִ�У�$ git remote add origin https://github.com/scriptcn/scriptcn.github.io.git �Ͳ��ᱨ������
 
2. $ git push origin master
 
������ʾ��error:failed to push som refs to
 
����취��$ git pull origin master //�Ȱ�Զ�̷�����github������ļ�����������push ��ȥ��


