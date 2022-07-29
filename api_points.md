```


<!--  Tabel Users -->

GET: /users
data: {
    "ID": "2000016102",
    "Name": "Sheila Deswita Ariyanto",
    "Deskripsi": "Let Me Show You A Few Things About Me. So, Welcome To My Website\r\n",
    "IG_URL": "https://www.instagram.com/sheila.mdy/",
    "Github_URL": "https://github.com/sheiladesw",
    "Linkedin_URL": "https://www.linkedin.com/in/sheila-deswita-ariyanto-828a25203/"
}


GET: /users/[1]
data: {
    "ID": "2000016102",
    "Name": "Sheila Deswita Ariyanto",
    "Deskripsi": "Let Me Show You A Few Things About Me. So, Welcome To My Website\r\n",
    "IG_URL": "https://www.instagram.com/sheila.mdy/",
    "Github_URL": "https://github.com/sheiladesw",
    "Linkedin_URL": "https://www.linkedin.com/in/sheila-deswita-ariyanto-828a25203/"
}


POST: /users
data: {
    "ID": "1",
    "Name": "Carissa Putri Ariyanto",
    "Deskripsi": "Keep going!!",
    "IG_URL": "https://www.instagram.com/sheila.mdy/",
    "Github_URL": "https://github.com/sheiladesw",
    "Linkedin_URL": "https://www.linkedin.com/in/sheila-deswita-ariyanto-828a25203/"
}


PUT: /users[2]
data: {
    "ID": "291202",
    "Name": "Sheila Desw",
    "Deskripsi": "Let Me Show You A Few Things About Me. So, Welcome To My Website\r\n",
    "IG_URL": "https://www.instagram.com/sheila.mdy/",
    "Github_URL": "https://github.com/sheiladesw",
    "Linkedin_URL": "https://www.linkedin.com/in/sheila-deswita-ariyanto-828a25203/"
}


<!--  Tabel Portofolio -->

GET: /portofolio
data:[
{
    "ID": "1",
    "Title": "My Project",
    "Description": "Project ini menampilkan prototype aplikasi bernama padi.in",
    "Thumbnail_URL": "https://www.figma.com/file/Hsc5ImOKD9tmj5OlXNet2d/Prototype-Trefesta-Co.?node-id=0%3A1",
    "Picture": "http://sheiladesw.my.id/img/ccc.png"
},
{
    "ID": "2",
    "Title": "My Project",
    "Description": "Project ini merupakan project kelompok bernama sisthreehood, disini kami diminta untuk membuat tampilan front-end sebuah website.",
    "Thumbnail_URL": "https://sheiladesw.github.io/StartEFH_SisthreehoodTeam/",
    "Picture": "http://sheiladesw.my.id/img/bbb.png"
}
]

GET: /portofolio/[1]
data:{
{
    "ID": "1",
    "Title": "My Project",
    "Description": "Project ini menampilkan prototype aplikasi bernama padi.in",
    "Thumbnail_URL": "https://www.figma.com/file/Hsc5ImOKD9tmj5OlXNet2d/Prototype-Trefesta-Co.?node-id=0%3A1",
    "Picture": "http://sheiladesw.my.id/img/ccc.png"
}


POST: /portofolio
data:{
    "ID": "2000016102",
    "Title": "My Project",
    "Description": "Project ini menampilkan prototype aplikasi EDC Safety Child",
    "Thumbnail_URL": "https://www.figma.com/file/Hsc5ImOKD9tmj5OlXNet2d/Prototype-Trefesta-Co.?node-id=0%3A1",
    "Picture": "http://sheiladesw.my.id/img/ccc.png"
}

PUT: /portofolio/[6]
data:{
    "ID": "2",
    "Title": "My Project 2",
    "Description": "Project ini merupakan project kelompok bernama sisthreehood, disini kami diminta untuk membuat tampilan front-end sebuah website, peran saya disini adalah sebagai Design grafis",
    "Thumbnail_URL": "https://sheiladesw.github.io/StartEFH_SisthreehoodTeam/",
    "Picture": "http://sheiladesw.my.id/img/bbb.png"
}


<!--  Tabel Artikel -->

GET: /artikel
data:[
{
      "ID": "2",
      "Title": "Opini-Generasi Muda Berkualitas Anti-NAPZA",
      "Content": "Penyalahgunaan NAPZA sudah menjadi momok bagi masyarakat dan pemerintah sebagai wabah..",
      "Author": "Sheila Deswita Ariyanto",
      "Date": "2021-08-19",
      "SourcePic": "Canva"
},
{
      "ID": "1",
      "Title": "Quarter Life Crisis",
      "Content": "Saat seseorang berusia 18–30 tahun merasa tidak memiliki arah, khawatir, bingung, dan galau akan ketidakpastian",
      "Author": "alodokter",
      "Date": "2020-11-12",
      "SourcePic": "pinteres"
},
{
      "ID": "3",
      "Title": "Marketing Communication\r\n",
      "Content": "Marketing communication mengacu pada sarana yang diadopsi oleh perusahaan untuk ..",
      "Author": "Bussiness Jargona",
      "Date": "2018-03-16",
      "SourcePic": "Pinterest"
},
{
      "ID": "4",
      "Title": "Resto Kopi Konsep Unik di Kutabumi, Incaran Kaum Milenial\r\n",
      "Content": "Kopi awalnya dicap sebagai minuman orang tua, kini banyak diminati anak muda. Semua tampilan\r\n\r\n",
      "Author": " wartabanten.id\r\n\r\n",
      "Date": "2021-03-16",
      "SourcePic": " Pinterest\r\n"
}
]


GET: /artikel/[2]
data:{
      "ID": "2",
      "Title": "Opini-Generasi Muda Berkualitas Anti-NAPZA",
      "Content": "Penyalahgunaan NAPZA sudah menjadi momok bagi masyarakat dan pemerintah sebagai wabah..",
      "Author": "Sheila Deswita Ariyanto",
      "Date": "2021-08-19",
      "SourcePic": "Canva"
}
  
  
POST: /artikel
data:{
      "ID": "5",
      "Title": "Apa sih UI/UX itu?",
      "Content": "Desain UI dan UX adalah dua pekerjaan yang tidak bisa dipisahkan. Keduanya memegang peran pent..",
      "Author": "Sheila Deswita Ariyanto",
      "Date": "2022-07-25",
      "SourcePic": "Freepik"
}


PUT: /artikel/[8]
data:{
      "ID": "2",
      "Title": "Generasi Muda Berkualitas Anti-NAPZA",
      "Content": "Penyalahgunaan NAPZA sudah menjadi momok bagi masyarakat dan pemerintah sebagai wabah..",
      "Author": "Sheila Deswita Ariyanto",
      "Date": "2021-08-19",
      "SourcePic": "Canva"
}


<!--  Tabel skill -->

GET: /skill
data:[
{
      "ID": "1",
      "Name": "M.Word",
      "Level": "Advance",
      "Picture": "http://sheiladesw.my.id/img/logo/m.word.png"
},
{
      "ID": "2",
      "Name": "Html",
      "Level": "Intermediate",
      "Picture": "http://sheiladesw.my.id/img/logo/html.png"
},
{
      "ID": "3",
      "Name": "Css",
      "Level": "Intermediate",
      "Picture": "http://sheiladesw.my.id/img/logo/css.png"
},
{
      "ID": "4",
      "Name": "Figma",
      "Level": "Advanced",
      "Picture": "http://sheiladesw.my.id/img/logo/figma.png"
},
{
      "ID": "5",
      "Name": "Python",
      "Level": "Intermediate",
      "Picture": "http://sheiladesw.my.id/img/logo/python.png"
},
{
      "ID": "6",
      "Name": "SPSS",
      "Level": "Intermediate",
      "Picture": "http://sheiladesw.my.id/img/logo/spss.png"
},
{
      "ID": "7",
      "Name": "SQLYog",
      "Level": "Advanced",
      "Picture": "http://sheiladesw.my.id/img/logo/sql.png"
},
{
      "ID": "8",
      "Name": "QGIS",
      "Level": "Advanced",
      "Picture": "http://sheiladesw.my.id/img/logo/sig.png"
}
]


GET: /portofolio/[2]
data:{
      "Name": "My Project",
      "Picture": "http://sheiladesw.my.id/img/bbb.png"
}

      
POST: /skill
data:{
      "ID": "9",
      "Name": "Canva",
      "Level": "Advanced",
      "Picture": "http://sheiladesw.my.id/img/logo/sig.png"
 }


PUT: /artikel/[7]
data:{
      "Name": "Opini-Generasi Muda Berkualitas Anti-NAPZA",
      "Picture": "Canva"
}

```
