# Exploring-Objects-and-Arrays
By Sarah Zaheer and Chloe Kim


### Add two more "people" object literals to the people array.

var people = [
  {
    name: "J.D. Zamfirescu",
    food: "宫保鸡丁",
    color: "blue"
  },
  {
    name: "Adam Smith",
    food: "小笼包",
    color: "red"
  },
  
  {
    name: "Sarah",
    food: "tofu",
    color: "black"
  },
  
  {
    name: "Chloe",
    food: "beans",
    color: "yellow"
  }

  
  
];

textAlign(CENTER);

for (var i = 0; i < people.length; i += 1) {
  fill(0);
  textSize(15);
  text("❤️", width/2, height/2-10);
  textSize(40);
  text(people[i].name, width/2, height/2-30);
  fill(people[i].color);
  text(people[i].food, width/2, height/2+30);
}

### Fix the overlapping text issue by using the index variable i in the body of the for loop to modify the y coordinate of the drawn text.

#### One way of doing it:-

var people = [
  {
    name: "J.D. Zamfirescu",
    food: "宫保鸡丁",
    color: "blue"
    
    
  },
  {
    name: "Adam Smith",
    food: "小笼包",
    color: "red"
  },
  
  {
    name: "Sarah",
    food: "tofu",
    color: "black"
  },
  
  {
    name: "Chloe",
    food: "beans",
    color: "yellow"
  }

  
  
];

textAlign(CENTER);

for (var i = 0; i < people.length; i += 1) {
  fill(0);
  textSize(15);
  clear ()
  text("❤️", width/2, height/2-10);
  textSize(40);
  text(people[i].name, width/2, height/2-30);
  fill(people[i].color);
  text(people[i].food, width/2, height/2+30);
}

#### Another way of doing it:-

var people = [
  {
    name: "J.D. Zamfirescu",
    food: "宫保鸡丁",
    color: "blue"
  },
  {
    name: "Adam Smith",
    food: "小笼包",
    color: "red"
  },
  
  {
    name: "Sarah",
    food: "tofu",
    color: "black"
  },
  
  {
    name: "Chloe",
    food: "beans",
    color: "yellow"
  }

  
  
];

textAlign(CENTER);

size= 10 
  var x= height/4  
for (var i = 0; i < people.length; i += 1) {
  fill(0);
  textSize(10);
	

  text("❤️", width/2, x-10);
  text(people[i].name, width/2, x-30);
  fill(people[i].color);
  text(people[i].food, width/2, x+30);
  x=x+100
 
}

### Add a property to all objects for size; use it to change the font size of each person's words.

var people = [
  {
    name: "J.D. Zamfirescu",
    food: "宫保鸡丁",
    color: "blue"
  },
  {
    name: "Adam Smith",
    food: "小笼包",
    color: "red"
  },
  
  {
    name: "Sarah",
    food: "tofu",
    color: "black"
  },
  
  {
    name: "Chloe",
    food: "beans",
    color: "yellow"
  }

  
  
];

textAlign(CENTER);

size= 10 
  var x= height/4  
for (var i = 0; i < people.length; i += 1) {
  fill(0);
  textSize(10);
	

  text("❤️", width/2, x-10);
  textSize(size);
  text(people[i].name, width/2, x-30);
  fill(people[i].color);
  text(people[i].food, width/2, x+30);
  x=x+100
  size=size+5
}







