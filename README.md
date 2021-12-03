# country-info
# This is my core javaScript project.
# This projest is countries information showing here...
# This is api use in this project.
# API : https://restcountries.com/v2/all

# Here is javascript code:
# const loadCountries = () => {
#    const URL = `https://restcountries.com/v2/all`;
#    fetch(URL)
#        .then((res) => res.json())
#        .then((data) => displauCountries(data));
# }

# // another funtion which display all data of countries...
# const displauCountries = (countries) => {
#    const countriesHTML = countries.map((country) => getCountryHtml(country));
#    const constent = document.getElementById('root');
#    const allContent = countriesHTML.join(' ');
#    constent.innerHTML = allContent;
# }

# //this funtion return to html dom....
# const getCountryHtml = (country) => {
#   return (`
#        <div class="childDiv">
#            <img src="${country.flag? country.flag: 'Empty This Data'}" alt="country">
#            <h2> Country Name: ${country.name? country.name: 'Empty This Data'}  </h2>
#            <p> Region : ${country.region? country.region: 'Empty This Data'} </p>
#            <p> Population : ${country.population? country.population: 'Empty This Data'} </p>
#            <p> Aria : ${country.area? country.area: 'Empty This Data'} </p>
#            <p> Capital : ${country.capital? country.capital: 'Empty This Data'} </p>
#        </div>
#    `);
# }
# loadCountries();