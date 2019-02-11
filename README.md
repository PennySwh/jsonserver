// GET
// 获取所有用户信息
localhost:3000

// 获取id为1的用户信息
localhost:3000/users/1

// 获取公司的所有信息
localhost:3000/companies

// 获取单个公司的信息
localhost:3000/companies/1

// 获取所有公司id为3的用户
localhost:3000/companies/3/users

// 根据公司名字获取公司信息
localhost:3000/companies?name=Microsoft

// 根据多个公司名字获取公司信息
localhost:3000/companies?name=Microsoft&name=Google

// 获取一页中只有两条数据
localhost:3000/companies?_page=1&_limit=2

// 升序排序 asc升序 desc降序
localhost:3000/companies?_sort=name&_order=asc

// 获取年龄大于等于21
localhost:3000/users?age_gte=21

// 获取年龄大于等于21，小于等于22
localhost:3000/users?age_gte=21&age_lte=22

// 搜索用户信息
localhost:3000/users?q=Penny