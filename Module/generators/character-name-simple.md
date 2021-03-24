---
name: Character Name Generator
slug: character-name-generator
---
### Character Name Generator
Use the following generator to quickly generate a few names based on the character's race (or culture) and gender.

<div style="margin-bottom:15px; text-align:center;">
    <button id="buttonGenerateName" onclick="generateName()"> 
        Generate Name 
    </button> 
</div>

<hr/>

<h4 style="text-align:center;"><span id="givenName"></span> <span id="familyName"></span></h4>

<script>

    function generateName() {
        givenName.innerHTML = 
            dragonbornFemale[Math.floor(Math.random() * dragonbornFemale.length)];
        familyName.innerHTML = 
            dragonbornFamily[Math.floor(Math.random() * dragonbornFamily.length)];
    }

    // Data
    const dragonbornFemale = ["Aakra","Aasathra","Antrara","Arava","Biri","Blendaeth","Burana","Chassath","Daar","Dentratha","Doudra","Driindar","Eggren","Farideh","Findex","Furrele","Gesrethe","Gilkass","Harann","Havilar","Hethress","Hillanot","Jaxi","Jezean","Jheri","Kadana","Kava","Korinn","Megren","Mijira","Mishann","Nala","Nuthra","Perra","Pogranix","Pyxrin","Quespa","Raiann","Rezena","Ruloth","Saphara","Savaran","Surina","Sora","Synthrin","Tatyan","Thava","Uadjit","Vezera","Zykroff"];
    const dragonbornMale = ["Adrex","Arjhan","Azzakh","Balasar","Baradad","Bharash","Bidreked","Dadalan","Dazzazn","Direcris","Donaar","Fax","Gargax","Ghesh","Gorbundus","Greethen","Heskan","Hirrathak","Ildrex","Kaladan","Kerkad","Kiirith","Kriv","Maagog","Medrash","Mehen","Mozikth","Mreksh","Mugrunden","Nadarr","Nithther","Norkruuth","Nykkan","Pandjed","Patrin","Pijjirik","Quarethon","Rathkran","Rhogar","Rivaan","Sethrekar","Sharnash","Shedinn","Srorthen","Tarhun","Torinn","Trynnicus","Valorean","Vrondiss","Zedaar"];
    const dragonbornFamily = ["Belarrak","Belnak","Churiarajachi"];

</script> 