Втора лабораториска вежба по Софтверско инженерство

Маргарита Стојковска, број на индекс:121232

2.) Control Flow Graph

<img width="411" alt="THIS" src="https://github.com/SI121232/SI_2023_lab2_121232/assets/103042343/5ef3dfbd-de98-4996-a784-27b743754e26">

3.) Цикломатска комплексност

Користејќи ја формулата E-N+2 (E-број на ребра, N-број на јазли, Е-35, N-26), добиваме резултат дека цикломатската комплексност е 11 

4.) Тест случаи според Every Branch критериум

- User е null
- Password е null
- User и листата се null
- Password се совпаѓа со некој друг password и е подолг од 8 карактери
- Password е уникатен и е пократок од 8 карактери
- Password не содржи специјални карактери
- Password содржи празни места
- Е-mail е null
- Password и е-mail се null

5.) Multiple Conditions

if (user==null || user.getPassword()==null || user.getEmail()==null)

- F || F || F -> user != null, user.getPassword() != null, user.getEmail() != null
- F || F || T -> user != null, user.getPassword() != null, user.getEmail() == null
- T || X || X -> user == null, user.getPassword() == anything, user.getEmail() == anything
- F || T || X -> user != null, user.getPassword() == null, user.getEmail() == anything



