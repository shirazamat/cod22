# cod22
function fa (val,pow) {
    if (pow == 1) {
        return val 
    }
    
    return val * fa(val,pow-1)
}

function ba (num) {
    if (fa(2,9) == num) {
        return console.log ('YES')
    }
    else {
        return console.log('NO')
    }
}


console.log(ba(90));
