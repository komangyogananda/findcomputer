# Daftar Isi
- [Daftar Isi](#daftar-isi)
- [Identitas](#identitas)
- [Find Computer SEA 2020](#find-computer-sea-2020)
  - [Deskripsi](#deskripsi)
  - [Result](#result)

# Identitas
Komang Yogananda Mahaputra Wisna  
Institut Teknologi Sepuluh Nopember

# Find Computer SEA 2020


## Deskripsi
Find computer merupakan sebuah proyek web yang menjadi salah satu tugas dalam Software Engineering Academy 2020. Deskripsi tugas adapun sebagai berikut:

> Suppose you and your friend will start reselling components of the computer. In this pandemic era, you can’t open your shop. You’ve just realized that your shop needs to move forward. You decided to build a website for your shop so transactions can be done online. You’ve discussed with your friend about what the requirements are, and here is the list:  
> ### Backend
> Note: You must implement the backend with Java Spring Boot.  
> #### User Requirements :
> - User can register, login, and logout.
> - User can update their profile information.
> - User can add their items to be sold.
>    - Item sold by an user must have Item name, Item description, Itemcategory, Item Price, and Item owner.
> - User can see their own items in the shop.
> - User can remove their own items from the shop.
> - User can update their own items from the shop.
> - User can see other User items.
> - User can search for specific other User items in the shop.
> - User can search other User items by category in the shop.
> - Categories: RAM, Processor, VGA, Motherboard, Storage.
> - User can buy other User items (price doesn’t count, so when you click buy the item will be automatically bought).
> - User can’t buy their own products.
> - After an item is bought, that item doesn’t exist anymore.
> ### FrontEnd
> You can use any frontend frameworks you’re familiar with (ex: Thymeleaf, React.js, etc). You’re free to design your own web, but make sure it is good enough to be seen. Better design is a plus.

## Result
Proyek ini menggunakan arsitektur Client-Server. Proyek ini dibagi menjadi 2 submodules:  
- [Module Backend](https://github.com/komangyogananda/findcomputer-be)  
  Module backend dikerjakan dengan menggunakan framework Spring Boot. Arsitektur yang digunakan adalah REST Api dengan authentikasi menggunakan JWT. Database yang digunakan pada proyek ini adalah MySQL serta Storage dari Google Cloud Storage yang digunakan untuk menyimpan gambar Items pengguna. Untuk keterangan deployment local dapat memeriksa github module backend.

- [Module Frontend](https://github.com/komangyogananda/findcomputer-fe)  
  Module frontend dikerjakan dengan menggunakan library ReactJS dengan menggunakan Typescript. Frontend menggunakan authentikasi JWT untuk setiap requestnya (terutama request yang memerlukan authentikasi). JWT Token disimpan didalam localstorage sehingga user tidak perlu login setiap refresh page.

Hasil dari proyek ini dapat dilihat pada https://findcomputer-kulguy.netlify.app/ 

