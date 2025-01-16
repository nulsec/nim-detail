Nomor Induk Mahasiswa (NIM)

Check NIM and Diploma Numbers for College Graduates must be done to find out that they have been registered with Pddikti and Civil. If the identity when checking the data is found, it can be said that friends have been registered as students or alumni for those who have graduated from the college.

In addition to the National Student Identification Number (NISN) for students in SD/MI/Package A, SMP/MTs/Package B and SMA/MA/SMK/Package C schools as a national identity. As students at public and private universities, they also have a Student Identification Number (NIM) as a national recognition for each student.

In order to avoid the words of obtaining a fake diploma and knowing the authenticity of a diploma, the Ministry of Education and Culture has collected student record data from all elementary and middle school students to universities into 1 data bank as a digital archive. All of that so that everyone can see and check the authenticity of a diploma. Starting from the SD/MI/Package A diploma, SMP/MTs/Package B diploma, SMA/MA/SMK/Package C certificates and certificates from public and private universities.

In general, many students want to know the Student Identification Number (NIM) on the form when filling out the SKS form to be taken as well as alumni who have become teachers or education staff when filling out forms to complete CPNS/PPPK/Education History registration data in DAPODIK management.

Diploma numbers from college graduates are also usually checked online when filing for CPNS and PPPK registration. If the track record of the applicant's identity is found, it will pass the first stage of registration and continue to the next stage for filing.

It is important for new students, especially to view the pddikti page to find out updates while studying in college and find out what credits have been taken and the amount as a requirement for submitting a thesis exam with a minimum total credit limit. And it is also very important for alumni to check on the civil portal to find out that their diploma number has been registered with the Kemendikbudristek data bank.


Nomor Induk Mahasiswa (NIM)

How To

Get Nim 

````
CURL *hnd = curl_easy_init();

curl_easy_setopt(hnd, CURLOPT_CUSTOMREQUEST, "GET");
curl_easy_setopt(hnd, CURLOPT_URL, "https://cek-nim-detail.p.rapidapi.com/getmhs?name=Nama Mahasiswa");

struct curl_slist *headers = NULL;
headers = curl_slist_append(headers, "X-RapidAPI-Key: key");
headers = curl_slist_append(headers, "X-RapidAPI-Host: cek-nim-detail.p.rapidapi.com");
curl_easy_setopt(hnd, CURLOPT_HTTPHEADER, headers);

CURLcode ret = curl_easy_perform(hnd);
````

Respon

````
[
  {
    "nama": "Nama Lengkap",
    "nim": "123123",
    "nama_pt": "UNIVERSITAS A",
    "sinkatan_pt": "UNIV",
    "nama_prodi": "JURUSAN"
  },
  {
    "nama": "Nama Lengkap",
    "nim": "123123",
    "nama_pt": "UNIVERSITAS A",
    "sinkatan_pt": "UNIV",
    "nama_prodi": "JURUSAN"
  }
]
````

Get Detail From NIM

````
CURL *hnd = curl_easy_init();

curl_easy_setopt(hnd, CURLOPT_CUSTOMREQUEST, "GET");
curl_easy_setopt(hnd, CURLOPT_URL, "https://cek-nim-detail.p.rapidapi.com/mhs?no=123123");

struct curl_slist *headers = NULL;
headers = curl_slist_append(headers, "X-RapidAPI-Key: key");
headers = curl_slist_append(headers, "X-RapidAPI-Host: cek-nim-detail.p.rapidapi.com");
curl_easy_setopt(hnd, CURLOPT_HTTPHEADER, headers);

CURLcode ret = curl_easy_perform(hnd);
````

Id No Result 
Cek On PDDIKTI if Respon Detail NULL Mean Data Not Input On PDDIKTI 



Result Like This

```
{
  "ID": "F9524C63-51EA-48B3-9AC6-32A9B95794D6",
  "NAMA": "NAMA LENGKAP",
  "JENIS_KELAMIN": "L",
  "TGL_LAHIR": "1988-05-14",
  "TEMPAT_LAHIR": "TEMPAT LAHIR",
  "ALAMAT_JALAN": "-",
  "ALAMAT_KELURAHAN": "-",
  "ALAMAT_KAB_KOTA_ID": "ID KOTA",
  "ALAMAT_KAB_KOTA_NAMA": "TIDAK ADA",
  "EMAIL": "EMAIL@GMAIL.COM",
  "AGAMA_ID": "1",
  "AGAMA_NAMA": "AGAMA",
  "IBU_KANDUNG": "-",
  "KEWARGANEGARAAN": "INDONESIA",
  "TERDAFTAR_ID": "F9675292-7C65-4104-AB18-69245B93B581",
  "TERDAFTAR_ID_PT": "002CBEF6-B16D-4117-892F-CB0372400A61",
  "TERDAFTAR_KODE_PT": "123123",
  "TERDAFTAR_NAMA_PT": "UNIV",
  "TERDAFTAR_ID_PRODI": "866E69B4-B952-44DC-A906-A305F5B4D09F",
  "TERDAFTAR_KODE_PRODI": "63412",
  "TERDAFTAR_NAMA_PRODI": "JURUSAN",
  "TERDAFTAR_STATUS_PT": "A",
  "TERDAFTAR_JENJANG_DIDIK_ID": "22",
  "TERDAFTAR_JENJANG_DIDIK_NAMA": "D3",
  "TERDAFTAR_NIM": "123123",
  "TERDAFTAR_TGL_MASUK": "2006-09-18",
  "TERDAFTAR_TGL_KELUAR": "2010-03-31",
  "TERDAFTAR_SMT_MULAI": "20061",
  "TERDAFTAR_SMT_TEMPUH": "8",
  "TERDAFTAR_SKS": "120",
  "TERDAFTAR_IPK": "3",
  "TERDAFTAR_NO_IJAZAH": "03/KOP.XII/ASMI-YHB/D3.S/2010",
  "TERDAFTAR_TGL_SK_YUDISIUM": "2010-03-31",
  "TERDAFTAR_STATUS": "L",
  "TERDAFTAR_JENIS_DAFTAR_ID": "1",
  "TERDAFTAR_JENIS_DAFTAR_NAMA": "PESERTA DIDIK BARU",
  "TERDAFTAR_JENIS_KELUAR_ID": "1",
  "TERDAFTAR_JENIS_KELUAR_KET": "LULUS",
  "TERDAFTAR_SKS_SEMESTER": "8",
  "TERDAFTAR_IPS": "3"
}
```

https://rapidapi.com/nulsec/api/cek-nim-detail
