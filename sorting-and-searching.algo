let sort = (arr, val) => {

    arr.push(val)

    for(let i = 0; i < arr.length; i++){
        let current = arr[i];

        let j = i - 1
        
    while( (j > -1) && (current < arr[j])){
     
        arr[j + 1] = arr[j]
       

        j--;  
        
    }
    arr[j + 1] = current
   
    

    }
return ` new stack: ${arr}`
}

console.log(sort([2, 4, 5, 20], 14)) //new stack: 2,4,5,14,20