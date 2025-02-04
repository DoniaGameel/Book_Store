<div align="center">
    <h1 align='center'>⚡️<i>Book store</i>⚡️</h1>
    <p>A desktop application that enables the user to buy, sell, borrow, lend, donate, take for free or order books. the user can also show seminars and shipping companies.</p>
</div>

<details open="open">
<summary>
<h2 style="display:inline">📝 Table of Contents</h2>
</summary>

- [📑 About](#about)
- [⛏️ Built With](#built-with)
- [📷 ScreenShots](#screenshots)
- [📂 Features](#features)
- [📑 Er Diagram](#er)
- [📑 DataBase Schema](#schema)
- [🔒 DataBase Restrictions](#restrictions)
- [✍️ Contributors](#contributors)

</details>

---

## 📑 About <a name = "about"></a>

- A desktop application that enables the user to buy, sell, borrow, lend, donate, take for free or order books. the user can also show seminars.
- It is a college project for the data base course. The aim is to apply the basic concepts learnt in the course.


## ⛏️ Built with <a name = "built-with"></a>

- C#
- SQL-server


## 📷 screenshots <a name = "screenshots"></a>

![collage (9)](https://user-images.githubusercontent.com/90224487/215482017-7d4cf3da-6ee8-4bad-8a81-7ae257f30864.jpg)

![collage (11)](https://user-images.githubusercontent.com/90224487/215483597-dbf1620f-bed1-4b7e-b203-4eef3e22719a.jpg)

![collage (12)](https://user-images.githubusercontent.com/90224487/215484288-6f4fed8b-e9c5-4488-aaf1-b9f543d77d76.jpg)

![collage (13)](https://user-images.githubusercontent.com/90224487/215484709-c31582a1-10a2-40ef-94a1-ef04e5faa00e.jpg)

![collage (14)](https://user-images.githubusercontent.com/90224487/215485151-9fb36b14-2937-4c9a-8682-4b150ff30d94.jpg)

![collage (15)](https://user-images.githubusercontent.com/90224487/215486836-d1599df8-0058-4303-8cad-9a9823a59cfd.jpg)

![collage (16)](https://user-images.githubusercontent.com/90224487/215487238-850c8a73-d3cc-4a7b-9718-f436b015195a.jpg)

![collage (17)](https://user-images.githubusercontent.com/90224487/215487628-22537665-6db2-4c9c-ad6f-498a34354524.jpg)

![collage (18)](https://user-images.githubusercontent.com/90224487/215488009-4273b4c0-3712-4c64-bcce-6e4342cc0870.jpg)

![collage (19)](https://user-images.githubusercontent.com/90224487/215488585-8aebb59b-679b-4550-baf2-e4ab60772de4.jpg)

![collage (20)](https://user-images.githubusercontent.com/90224487/215488990-ecf26201-41be-48df-9584-c65d5a552224.jpg)

![collage (21)](https://user-images.githubusercontent.com/90224487/215490556-c14a85d5-5392-42e4-92f6-2f83395bcb0d.jpg)

![collage (22)](https://user-images.githubusercontent.com/90224487/215491188-7cf4eef5-b981-4e79-97d7-f8b223d661c3.jpg)



## 📂 Features <a name = "features"></a>

<details>
<summary>
<h4 style="display:inline">
<strong><em>🔒 User Authentication</em></strong></h4>
</summary>

- Sign up
- Login in
- Change password  
</details>

<details>
<summary>
<h4 style="display:inline">
<strong><em> 🙍‍♂️ User Profile </em></strong></h4>
</summary>

- Sell books
- Lend books
- Donate books
- Order unavailable books
- Buy books
- Borrow books
- Take books for free
- Show his/her orders
- Show seminars
- Show shipping companies
- Logout
    
</details>

<details>
<summary>
<h4 style="display:inline">
<strong><em> 🙍‍♂️ Admin Profile </em></strong></h4>
</summary>

- Login
- Add/Delete shipping companies
- Add/Delete seminars
- Add admins
- Change password
    
</details>

## 📑 ER Diagram <a name = "er"></a>

![My Image](imgs/ER_1.jpg)

![My Image](imgs/ER_2.jpg)

Separated figures just to be readable

## 📑 DataBase Schema <a name = "schema"></a>

![My Image](imgs/Schema.jpg)

## 🔒 DataBase Restrictions <a name = "restrictions"></a>

**-Username and email are unique for each user and 
admin.**

**-The tuple of a book stores only one version of the 
book that is added by a certain user. If another user 
added the book I will consider it as another instance.**

**-Each book has one category.** 

**-There are no two seminars on the same date with the 
same topic name.**

**-A publisher or a shipping company can have many 
addresses and many phone numbers as it has several 
branches.**

**-The book has only one author and one publisher.** 

**-If a user offered a book to buy he will specify the 
price.**

**-If a user offered a book to borrow he will specify the 
period the other user will take the book for.**

## ✍️ Contributors <a name = "contributors"></a>

[Asmaa Adel](https://github.com/asmaaadel0)

[Donia Gameel](https://github.com/DoniaGameel)

[Heba Ashraf](https://github.com/hebaashraf21)

[Salma Ragab](https://github.com/SalmaRagab279)
