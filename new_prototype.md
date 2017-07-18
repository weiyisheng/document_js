### what's "__proto__" and "prototype":
  "__proto__" property is an reference to the value of its constructor’s “prototype” 

### what JS doing in a New process ?
  ex: new Vehicle()
  1. create a new empty object
  2. set the constructor property of the object to the Vehicle, (It won’t show up if you enumerate the properties of the object)
  3. set up the object to delegate to Vehicle.prototype (__proto__ => Vehicle.prototype)
  4. call the constructor: Vehicle()
  
  
