// GET
// ��ȡ�����û���Ϣ
localhost:3000

// ��ȡidΪ1���û���Ϣ
localhost:3000/users/1

// ��ȡ��˾��������Ϣ
localhost:3000/companies

// ��ȡ������˾����Ϣ
localhost:3000/companies/1

// ��ȡ���й�˾idΪ3���û�
localhost:3000/companies/3/users

// ���ݹ�˾���ֻ�ȡ��˾��Ϣ
localhost:3000/companies?name=Microsoft

// ���ݶ����˾���ֻ�ȡ��˾��Ϣ
localhost:3000/companies?name=Microsoft&name=Google

// ��ȡһҳ��ֻ����������
localhost:3000/companies?_page=1&_limit=2

// �������� asc���� desc����
localhost:3000/companies?_sort=name&_order=asc

// ��ȡ������ڵ���21
localhost:3000/users?age_gte=21

// ��ȡ������ڵ���21��С�ڵ���22
localhost:3000/users?age_gte=21&age_lte=22

// �����û���Ϣ
localhost:3000/users?q=Penny