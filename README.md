<h1>Ruby Arrays and Hashes Quiz</h1>
<h2>Exercise A</h2>
<h3>Given the following data structure:</h3>
  <pre><code>stops = [ "Croy", "Cumbernauld", "Falkirk High", "Linlithgow", "Livingston", "Haymarket" ]</code></pre>
<h3>Complete these tasks:</h3>
<ol>
<li>Add "Edinburgh Waverley" to the end of the array</li>
<li>Add "Glasgow Queen St" to the start of the array</li>
<li>Add "Polmont" at the appropriate point (between "Falkirk High" and "Linlithgow")</li>
<li>Print out the index position of "Linlithgow"</li>
<li>Remove "Livingston" from the array using its name</li>
<li>Delete "Cumbernauld" from the array by index</li>
<li>Print the number of stops there are in the array?</li>
<li>Show as many ways as you can to return "Falkirk High" from the array?</li>
<li>Reverse the positions of the stops in the array</li>
<li>Print out all the stops using a for loop</li>
</ol>
<h2>Exercise B</h2>
<h3>Given the following data structure:</h3>
  <pre><code>
  users = {
  "Jonathan" => {
    :twitter => "jonnyt",
    :lottery_numbers => [6, 12, 49, 33, 45, 20],
    :home_town => "Stirling",
    :pets => [
    {
      :name => "fluffy",
      :species => "cat"
    },
    {
      :name => "fido",
      :species => "dog"
    },
    {
      :name => "spike",
      :species => "dog"
    }
  ]  
  },
  "Erik" => {
    :twitter => "eriksf",
    :lottery_numbers => [18, 34, 8, 11, 24],
    :home_town => "Linlithgow",
    :pets => [
    {
      :name => "nemo",
      :species => "fish"
    },
    {
      :name => "kevin",
      :species => "fish"
    },
    {
      :name => "spike",
      :species => "dog"
    },
    {
      :name => "rupert",
      :species => "parrot"
    }
  ]
  },
  "Avril" => {
    :twitter => "bridgpally",
    :lottery_numbers => [12, 14, 33, 38, 9, 25],
    :home_town => "Dunbar",
    :pets => [
      {
        :name => "monty",
        :species => "snake"
      }
    ]
  }
}
  </code></pre>
<h3>Complete these tasks:</h3>
<ol>
<li>Get Jonathan’s Twitter handle (i.e. the string "jonnyt")</li>
<li>Get Erik’s hometown</li>
<li>Get the array of Erik’s lottery numbers</li>
<li>Get the species of Avril’s pet Monty</li>
<li>Get the smallest of Erik’s lottery numbers</li>
<li>Return an array of Avril’s lottery numbers that are even</li>
<li>Erik is one lottery number short! Add the number 7 to be included in his lottery numbers</li>
<li>Change Erik’s hometown to Edinburgh</li>
<li>Add a pet dog to Erik called “Fluffy”</li>
<li>Add another person to the users hash</li>
</ol>
<h2>Exercise C</h2>
<h3>Given the following data structure:</h3>
  <pre><code>
  united_kingdom = [
  {
    name: "Scotland",
    population: 5295000,
    capital: "Edinburgh"
  },
  {
    name: "Wales",
    population: 3063000,
    capital: "Swansea"
  },
  {
    name: "England",
    population: 53010000,
    capital: "London"
  }
]
  </code></pre>
<h3>Complete these tasks:</h3>
<ol>
<li>Change the capital of Wales from "Swansea" to "Cardiff".</li>
<li>Create a Hash for Northern Ireland and add it to the united_kingdom array (The capital is Belfast, and the population is 1,811,000).</li>
<li>Use a loop to print the names of all the countries in the UK.</li>
<li>Use a loop to find the total population of the UK.</li>
</ol>
