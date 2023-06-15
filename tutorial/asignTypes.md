This is for object

type Person = {
name: string;
age?: number; //default or means the age is optional
};

/// Extends

  interface Person{
    name: string,
    age?: number;
  }

  interface Guy extends Person{
    profession: string;
  }

  type X = {
    a: string,
    b: number
  }

  type Y = X & {
    c: string,
    d: number;
  }

  // se puede convinar las dos formas
////

let person: Person = {
name : "Jhon",
age : 22,
};

let lostsOfPerson: Person[];
let role: [number, string]

let age: number | string; means that this variable can be of two types
let name: any: means that this variable can be any type. Is not recomended
