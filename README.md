# Ex04 Places Around Me

# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
main html 
```
<html>
    <head>
        <title>IMAGEMAP</title>
        <LINK REL="ICON" href="c:\Users\admin\Downloads\MAP.jpg"
    </head>
    <BODY>
        <H1><MARQUEE>🗺️⁀જ✈︎🗺️IMAGE MAP🗺️⁀જ✈︎🗺️</MARQUEE></H1>
<center><img src="c:\Users\admin\Pictures\Screenshots\Screenshot (196).png" usemap="#newmap"></center>




<map name="newmap">

        <area target="_blank" alt="Singapore Zoo" title="Singapore Zoo" href="Singapore_Zoo.HTML" coords="285,390,338,436" shape="rect">
        <area target="_blank" alt="wild wet park" title="wild wet park" href="wild_wet_park.HTML" coords="1209,527,1269,591" shape="rect">
        <area target="_blank" alt="Sembawang Hot Spring Park" title="Sembawang Hot Spring Park" href="Sembawang_Hot_Spring_Park.HTML" coords="453,206,508,266" shape="rect">
        <area target="_blank" alt="Jewel Changi Airport" title="Jewel Changi Air" href="Jewel_Changi_Airport.HTML" coords="1411,640,1475,697" shape="rect">
        <area target="_blank" alt="Stella Seaside Lounge" title="Stella Seaside Lounge" href="Stella_Seaside_Lounge.HTML" coords="1345,892,1399,941" shape="rect">
</map>
    </BODY>
</html>
```
Singapore_Zoo.HTML
```
<HTML>
    <HEAD>
        <TITLE>Singapore Zoo</TITLE>
        <LINK REL="ICON" href="c:\Users\admin\Desktop\singaporezoo.jpg">
    </HEAD>
    <BODY style="background-color: rgb(0, 234, 255); color: azure;">
        <H1 STYLE="color: whitesmoke; background-color: rgb(255, 0, 93);"><MARQUEE>Singapore Zoo</MARQUEE></H1>
        <CENTER><IMG SRC="c:\Users\admin\Desktop\singaporezoo.jpg" width="600" HEIGHT="300"></CENTER>
        <h3>
            <UL>
                <LI>The Singapore Zoo, officially known as the Mandai Wildlife Reserve, is one of the world’s most renowned wildlife parks. Situated in the lush Mandai rainforest in Singapore, it spans 26 hectares and is home to over 2,800 animals across 300 species, including mammals, birds, and reptiles. Established in 1973, the zoo is celebrated for its open-concept enclosures, offering visitors immersive experiences while ensuring the animals live in environments that closely resemble their natural habitats.</LI>
                <LI>Reptile Garden: Featuring Komodo dragons and a wide variety of snakes.</LI>
                <LI>Frozen Tundra: Home to Inuka, the first polar bear born in the tropics (a retired exhibit now reimagined with other cold-weather animals).</LI>
                <LI>Breakfast in the Wild: Dine alongside orangutans, an iconic experience that educates visitors about primates.</LI>
                <li>Animal Feedings: Visitors can feed giraffes, elephants, and even white rhinos under supervision.</li>
                <li>Kidzworld: A family-friendly zone with petting areas and water play areas.</li>
                <li>Night Safari & River Wonders: Located nearby, these sister attractions provide unique perspectives on nocturnal creatures and freshwater ecosystems.</li>
                <li>Singapore Zoo incorporates green initiatives like solar panels, water recycling, and educational programs on environmental conservation.</li>
                
            </UL>
        </h3>
    </BODY>
</HTML>
```
wild_wet_park.HTML
```
<HTML>
    <HEAD>
        <TITLE>Wild wet park</TITLE>
        <LINK REL="ICON" href="c:\Users\admin\Downloads\wild.avif">
    </HEAD>
    <BODY style="background-color: rgb(0, 234, 255); color: azure;">
        <H1 STYLE="color: whitesmoke; background-color: rgb(255, 0, 93);"><MARQUEE>Wild wet park</MARQUEE></H1>
        <CENTER><IMG SRC="c:\Users\admin\Downloads\wild.avif"  width="600" HEIGHT="300"></CENTER>
        <h3><UL>
            <LI>Wild Wild Wet is one of Singapore's largest and most popular water parks, located at Downtown East in Pasir Ris. Known for its exciting water slides, family-friendly attractions, and relaxing pools, it’s a favorite destination for locals and tourists seeking a fun-filled day of splashes and thrills.</LI>
            <LI>Wild Wild Wet, located at Downtown East in Singapore, is one of the country’s largest and most exciting water parks, offering a perfect blend of thrills and relaxation for visitors of all ages. With adrenaline-pumping rides like the Torpedo and Free Fall, it’s a haven for thrill-seekers, while family-friendly attractions such as the Shiok River and Kidz Zone ensure fun for everyone, including the little ones</LI>
            <LI>The park also features a wave pool, interactive playgrounds, and relaxing jacuzzis, making it ideal for group outings or family days. Equipped with modern facilities like lockers, food stalls, and shaded cabanas, Wild Wild Wet ensures a comfortable and enjoyable experience. Whether you’re chasing adventure or simply looking to cool off, this water park promises a splashing good time!.</LI>
            <LI>Wild Wild Wet is a vibrant water park in Singapore that promises fun and excitement for visitors of all ages. As one of the largest water parks in the region, it features a wide range of attractions, from heart-pounding slides like the Royal Flush and Free Fall to relaxing options such as the Shiok River and Tsunami Wave Pool.</LI>
            <li>Families with young children can enjoy interactive play areas like Professor’s Playground and Kidz Zone, ensuring a safe and fun environment for the little ones. The park’s thoughtful amenities, including well-maintained changing rooms, cabanas for relaxation, and a variety of dining options, enhance the overall experience.</li>
            
        </UL></h3>
    </BODY>
</HTML>
```
Sembawang_Hot_Spring_Park.HTML
```
<HTML>
    <HEAD>
        <TITLE>Sembawang Hot Spring Park</TITLE>
        <LINK REL="ICON" href="c:\Users\admin\Downloads\springpark.jpg">
    </HEAD>
    <BODY style="background-color: rgb(0, 234, 255); color: azure;">
        <H1 STYLE="color: whitesmoke; background-color: rgb(255, 0, 93);"><MARQUEE>Sembawang Hot Spring Park</MARQUEE></H1>
        <CENTER><IMG SRC="c:\Users\admin\Downloads\springpark.jpg"  width="600" HEIGHT="300"></CENTER>
        <h3><UL>
            <LI>Sembawang Hot Spring Park is a unique natural attraction located in the northern part of Singapore. It is the only hot spring on the mainland, offering visitors a serene and educational experience centered around the therapeutic benefits of natural hot spring water.</LI>
            <LI>The centerpiece of the park is a tiered fountain that channels the hot spring water for public use.Visitors can watch the steaming water cascade through the fountain, making it both functional and picturesque.</LI>
            <LI>The park incorporates rustic and kampong-style (village-style) aesthetics, paying homage to its historical roots.Historical elements, like old photos and educational boards, tell the story of how the hot spring was used by locals in the past, including during World War II.</LI>
            <LI>A must-try activity where visitors boil eggs in geothermal water at the specially designated egg-cooking stations.Watch them cook in 10-15 minutes while enjoying the company of friends and family.</LI>
            <li>Shallow pools are designed for foot soaking, with varying temperatures to suit different preferences.</li>
            <li>The park features a Floral Walk, showcasing native flora that thrives in the hot, humid environment.</li>
        </UL></h3>
    </BODY>
</HTML>
```
Jewel_Changi_Airport.HTML
```
<HTML>
    <HEAD>
        <TITLE>Jewel Changi Airport</TITLE>
        <LINK REL="ICON" href="c:\Users\admin\Downloads\89bf5983e9f5386474ce3b68190cc13f-jewel changi 12.avif">
    </HEAD>
    <BODY style="background-color: rgb(0, 234, 255); color: azure;">
        <H1 STYLE="color: whitesmoke; background-color: rgb(255, 0, 93);"><MARQUEE>Jewel Changi Airport</MARQUEE></H1>
        <CENTER><IMG SRC="c:\Users\admin\Downloads\89bf5983e9f5386474ce3b68190cc13f-jewel changi 12.avif"  width="600" HEIGHT="300"></CENTER>
        <h3><UL>
            <LI></LI>
            <LI>Jewel Changi Airport is an iconic lifestyle hub located at Singapore's Changi Airport, blending nature, retail, dining, and entertainment under one spectacular roof. Since its opening in April 2019, Jewel has become a must-visit destination for travelers and locals alike.</LI>
            <LI>World’s Tallest Indoor Waterfall: Standing at 40 meters, the Rain Vortex is a mesmerizing centerpiece. Water cascades through the circular opening of the Jewel's glass dome, creating a stunning visual and sensory experience.</LI>
            <LI>An interactive digital attraction that showcases the innovation and operations of Changi Airport through games, simulations, and multimedia exhibits.</LI>
            <li>operations, and innovations through games, simulations, and displays.</li>
            <li>Architectural Marvel: Designed by world-renowned architect Moshe Safdie, Jewel is a visually stunning structure that blends futuristic design with natural beauty.</li>
            <li>World-Class Entertainment: Attractions like the Rain Vortex, Canopy Park, and Changi Experience Studio provide hours of fun for all ages.</li>
        </UL></h3>
    </BODY>
</HTML>
```
Stella_Seaside_Lounge.HTML
```
<HTML>
    <HEAD>
        <TITLE>Stella Seaside Lounge</TITLE>
        <LINK REL="ICON" href="c:\Users\admin\Downloads\stella sea.avif">
    </HEAD>
    <BODY style="background-color: rgb(0, 234, 255); color: azure;">
        <H1 STYLE="color: whitesmoke; background-color: rgb(255, 0, 93);"><MARQUEE>Stella Seaside Lounge</MARQUEE></H1>
        <CENTER><IMG SRC="c:\Users\admin\Downloads\stella sea.avif" ALT="STYLE AND UNION" width="600" HEIGHT="300"></CENTER>
        <h3><UL>
            <LI>Stella Seaside Lounge is a coastal dining and lifestyle destination known for its laid-back ambiance, stunning sea views, and a menu designed to delight the senses. Positioned by the waterfront, this lounge offers a serene escape from the hustle and bustle of city life, making it an ideal spot for leisurely meals, romantic evenings, or group gatherings.</LI>
            <LI>Scenic Location: Nestled along the coastline, Stella Seaside Lounge provides panoramic views of the sea, offering a picturesque setting for both day and night.</LI>
            <LI>Relaxed Atmosphere: The lounge exudes a casual yet sophisticated vibe, blending contemporary décor with natural elements to create a cozy and inviting environment.</LI>
            <LI>Diverse Menu: Guests can enjoy a mix of international and local cuisines, including fresh seafood, gourmet salads, wood-fired pizzas, and refreshing beverages. The menu caters to a variety of tastes and dietary preferences.</LI>
            <li>Signature Cocktails: The bar serves an array of signature cocktails, premium wines, and refreshing mocktails, making it a great spot for unwinding.</li>
            <li>Entertainment & Events: Stella Seaside Lounge often hosts live music, DJ nights, and themed events, adding an extra layer of enjoyment to the dining experience.</li>
        </UL></h3>
    </BODY>
</HTML>
```

# OUTPUT
![screencapture-file-C-Users-admin-Desktop-HTML-STARTING-POINT-imagemap-html-2024-12-06-22_04_34](https://github.com/user-attachments/assets/95b2ad47-e9b5-4658-8dd5-815d408d2743)

![Screenshot (204)](https://github.com/user-attachments/assets/b72e8c8d-4d9a-4eba-9e64-92a8cc56cda4)
![Screenshot (205)](https://github.com/user-attachments/assets/ef1d4474-125d-41ff-8837-10a5aae76570)
![Screenshot (207)](https://github.com/user-attachments/assets/c6fdacd1-ef01-47cc-8f2d-ab1a184463dd)
![Screenshot (208)](https://github.com/user-attachments/assets/fa7bf037-f907-453a-8dd0-22d7e50d91ca)
![Screenshot (209)](https://github.com/user-attachments/assets/a883be54-6792-4882-a368-263ed1bdcc31)



# RESULT
The program for implementing image maps using HTML is executed successfully.
