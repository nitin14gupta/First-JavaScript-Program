// Task 1: Code a Person class
class Person {
  constructor(name = "Tom", age = 20, energy = 100) {
    this.name = name;
    this.age = age;
    this.energy = energy;
  }

  sleep() {
    this.energy += 10;
    console.log(`${this.name} is sleeping. Energy level increased to ${this.energy}.`);
  }

  doSomethingFun() {
    this.energy -= 10;
    console.log(`${this.name} is doing something fun. Energy level decreased to ${this.energy}.`);
  }
}
//Task 2
class Worker extends Person {
  constructor(name = "Tom", age = 20, energy = 100, xp = 0, hourlyWage = 10) {
    super(name, age, energy);
    this.xp = xp;
    this.hourlyWage = hourlyWage;
  }

  goToWork() {
    this.xp += 10;
    console.log(`${this.name} is going to work. Experience points increased to ${this.xp}.`);
  }
}
//Task 3
function intern() {
  const internObject = new Worker("Bob", 21, 110, 0, 10);
  internObject.goToWork();
  return internObject;
}
//Task 4
function manager() {
  const managerObject = new Worker("Alice", 30, 120, 100, 30);
  managerObject.doSomethingFun();
  return managerObject;
}

const newIntern = intern();
console.log(newIntern);

const newManager = manager();
console.log(newManager);
