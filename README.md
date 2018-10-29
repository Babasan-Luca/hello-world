# hello-world



function Vehicle(model, brand, horsePo, consumption, engineSize, tankCapacity, price) {
    this.model = model;
    this.brand = brand;
    this.horsePo = horsePo;
    this.consumption = consumption;
    this.engineSize = engineSize;
    this.tankCapacity = tankCapacity;
    this.price = price;
}

function startEngine(tankCapacity){
    console.log(tankCapacity);
}

function driveDistance(startKM, endKM,kmRange, tankCapacity, consumption){
    var startKM = 0;
    var endKM = endKM - startKM;
    var consumption = newDriveDistance - startKM;
    var kmRange = [];
    
    for( var i = startKM; i <= endKM; i++){
        kmRange.push(i);
    }
    return kmRange
}
    


Vehicle.prototype.timeToArrive = function(horsePo,time, consumption, maxSpeed ){
    this.horsePo = Vehicle.horsePo
    this.consumption = driveDistance.consumption;
    //Console.log(driveDistance.consumption);
    switch(this.horsePo){
        case (this.horsePo < 100) : value = (maxSpeed = 120 + "km/h");
            break;
        case (this.horsePo > 100 && this.horsePo < 140) : value = (maxSpeed = 220 + "km/h");
            break;
        case (this.horsePo > 140 && this.horsePo < 200) : value = (maxSpeed = 280 + "km/h");
            break;
        case (this.horsePo > 200) : value = (maxSpeed = 330 + "km/h");
} 
}

var Mercedes = new Vehicle ("c220", "mercedes", 150, 6 ,2000, 60+"L", 30000 + ' euro');

var Opel = new Vehicle ("corsa" , 'opel' , 120 , 5 , 1600, 40+"L", 25000 + 'euro');

var Mazda = new Vehicle ('Rx', 'mazda', 100 , 6 , 1200 , 45+'L' , 40000 + 'euro');


console.log(Mercedes.timeToArrive);

console.log(alert(""))
//......No more time to finish.
