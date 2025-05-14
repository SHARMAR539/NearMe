# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<html>
<head><title>My City</title></head>
<body>
<h1 align="center">
<font color="red" ><b align="center">Krishnagiri</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Rohith V (24900447)</b></font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Krishnagi_Fort" title="Krishnagi_Fort" href="krishnagiri_fort.html" coords="848,300,1030,388" shape="rect">
    <area target="" alt="Collector_Office" title="Collector_Office" href="collector_office.html" coords="527,57,677,134" shape="rect">
    <area target="" alt="Goverment_college" title="Goverment_college" href="college.html" coords="1287,417,1484,457" shape="rect">
    <area target="" alt="Shanthi_theatre" title="Shanthi_theatre" href="theater.html" coords="869,659,1023,714" shape="rect">
    <area target="" alt="District_Court" title="District_Court" href="court.html" coords="" shape="rect">
</map>
</center>
</body>
</html>

collector_office.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body  bgcolor="red">
    <h1 align="center"> Krishnagiri collector office</h1>
    <h2 style="font-size: large;"><li>Krishnagiri district is one of the 38 districts (a district in the north western part) of the state of Tamil Nadu, in India. <br> <li>This district is carved out from Dharmapuri District by 2004. The municipal town of Krishnagiri is the district headquarters. In Tamil Nadu, e-Governance was first introduced at Krishnagiri <br><li>district under the National e-Governance Project (NEGP) in revenue and social welfare departments on a pilot basis. <br> <li>[2][3] The district is one of the largest producers of mangoes in India.[4] As of 2011, the district had a population of 1,879,809 with a sex-ratio of 958 females for every 1,000 males. Hosur is the most populous city in the district</h2>
</body>
</html>

college.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="cyan">
    <h1 align="center">Goverment_college</h1>
    <p><b>Krishnagar Government College is the oldest college of the district. In 1846 Lord Hardinge approved the establishment proposal of the college. Nadia Raj Srishchandra Roy and Maharani Swarnamoyee Devi from Cossimbazar estate donated the land for it. The palatial building was made in 1856. The first principal was David Lester Richardson, famous educationist, ex-principal of the Presidency College, Calcutta. After that Marcus Gustavus Rochfort, Loper Lethbridge, Umesh Chandra Dutta, Jyoti Bhusan Bhadury, R.N Gilcriest, Eagerton Smith, Rakhalraj Biswas, and Satish Chandra De glorified the post. Notable personalities of the national freedom struggle, activists of political and social movements, academics, and intellectuals came out from the college. Ramtanu Lahiri, Md. Abdul Hai, Bishnu Dey, Subodh Chandra Sengupta, Khudiram Das, Sudhir Chakravarti were among the notable faculty members of the college.[5]</b></p>
</body>
</html>

cort.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="yellow">
    <h1 align="center">krishnagiri District Court</h1>
    <p><b>Krishnagiri is a district in the state of Tamil Nadu, India. The municipal town of Krishnagiri is the district headquarters. In Tamil Nadu, e-Governance was first introduced at Krishnagiri district under the National e-Governance Project (NEGP) in Revenue, Social Welfare departments on a pilot basis. The district is one of the two largest producers of Mangoes not only in Tamil Nadu but throughout India.The Krishnagiri district has prehistoric importance. Archeological sources confirm the presence of habitats of man kind during Paleolithic, Neolithic and Mesolithic Ages. Various rock paintings and rock carvings of Indus Valley civilization and Iron Age seen in this district support the historical significance of this district. The heart of 'Krishnagiri', 'Hosur' and 'Uthangarai' were known as 'Eyil Nadu', 'Murasu Nadu' and 'Kowoor Nadu' respectively. During Chola period, Krishnagiri region was called 'Nigarili Chola Mandlam' and 'Vidhugadhazhagi Nallur'. Under 'Nulamba' rule it was popular as 'Nulambadi' according to historical sources.Hero stones were erected for those whose lost their lives in pursuit of adventure. There was a tradition of erecting memorial stones for people who sacrifice their lives for the sake of their kings since 'Sangam Age'. These memorial stones were called 'Navagandam'. Plenty of memorial stones available in[...]

    </b></p>
</body>
</html>

krishnagiri_fort.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="gold">
    <h1 align="center">krishnagiri Fort</h1>
    <p><b>The fort and its surroundings were commonly referred to as "Baramahal," a term that linguistically translates to "twelve forts." This nomenclature reflects the presence of twelve hilltop forts in the region, including Krishnagiri Fort. This majestic fort was built under the aegis of the Vijayanagara Empire.[1][2]

        Jagadevarayar-I, a prominent chief of the Vijayanagara Empire, undertook a strategic migration from Hyderabad to Penukonda. Renowned for his exemplary valor, he played a crucial role in confronting and defeating the forces of the Bijapur army. The extraordinary bravery displayed by Jagadevarayar-I caught the attention of Ranga Raya-II, a representative of the Vijayanagara Empire stationed at Chandragiri.[2][3]</b></p>
</body>
</html>

theater.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body bgcolor="pink">
    <h1 align="center">Shanthi_Theatre</h1>
    <p><b>Shanti Theatre was built by G. Umapathy and D. Shanmuga Raja,[1] then the Raja of Sivaganga.[2] It was inaugurated on 12 January 1961 by then Chief Minister of Tamil Nadu, K. Kamaraj, and was the first deluxe air-conditioned theatre in Madras (now Chennai) with 1212 seats. The inaugural show was Srinivasa Kalyanam, and the first film to be released there officially was Thooya Ullam, followed by the Hindi film, Kalpana.[3] <br>

        Paava Mannippu, a Tamil film, was released in Shanti on 16 March 1961. When the film's original promoters were facing a repayment cash crisis, they approached star Sivaji Ganesan who agreed to invest, and eventually bought out the promoters.[3] The theatre had been owned by Ganesan's family ever since. The theatre is widely believed to have been named after Ganesan's daughter Shanti. According to Ganesan's nephew Giri Shanmugam, "Shanti Theatre became a landmark in the city because it was owned by the great Sivaji Ganesan. Watching a Sivaji movie in Shanti was on the must-to-do list, besides seeing Marina Beach and LIC – the only 14-storeyed building in the city then, for most visitors from other parts of Tamil Nadu."[3]
        
        After Paava Mannippu, the theatre proceeded to screen an additional 81 films starring Ganesan. Some of his films like Paava Mannippu, Thiruvilaiyadal, Vasantha Maligai, Thanga Pathakkam, Thirisoolam and Muthal Mariyathai became silver jubilee films,[a] while others achieved a 100-day run. During the celebrations of Karnan's 100th day in 1964, the theatre wore a festive look, with a real chariot created and kept for display. N. T. Rama Rao, who portrayed Krishna in that film, attended the event with various stars from the film.[3]</b></p>
</body>
</html>
```



## OUTPUT
![image](https://github.com/user-attachments/assets/d457b486-284b-4050-8fcb-123e63996c3e)
![image](https://github.com/user-attachments/assets/df66086a-0da3-4194-9283-206891bf899a)
![image](https://github.com/user-attachments/assets/d6f4e70d-80b3-4516-b145-7c2bea078846)
![image](https://github.com/user-attachments/assets/98775b8e-9674-4b66-9b96-261cc1a1aba6)
![image](https://github.com/user-attachments/assets/5bf74804-87b4-4f6b-9aad-c525d8107a3b)
![image](https://github.com/user-attachments/assets/9f74771a-bbcf-438c-841a-1dcab31d07e2)





## RESULT
The program for implementing image maps using HTML is executed successfully.
