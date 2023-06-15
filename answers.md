## Introductions

- Hi I'm Ravikumar Srinivasan is full stack developer for MERN and .NET.
- I have own Laptop and good internet connection (CORE I7 vPro 8th Gen (16GB RAM)).
- I'm in linkedin , stackoverflow and personal website domain expired.
- machine language
- I used Visual Studio,VS Code,Node js ,Mongodb,MSSQL,Sqldeveloper,Android Studio and Github
- I used Windows 11 OS 64 bit.
- I'm both frontend and backend developer.
- I interested in AI/ML.
- I learning python currently.

## Answers

- Find the longest word in a string.
    const str="The quick brown fox jumped over the lazy dog";
    var maxlenth=0;
    var maxWord="";
    str.split(' ').forEach((val)=>{
        if(val.length > maxlenth){
            maxlenth=val.length;
            maxWord=val;
        }} )
    
    console.log(maxWord)

- Repeat a string `n` times.
    var str="abc";
    var repeatTime=3;
    var repeateString=""
    for(let i=0;i<repeatTime;i++){
        repeateString +=str;
    }
    console.log(repeateString)

- Remove duplicates in an array
    const data=[1,20,3,1,3,3]
    //ES6
    console.log([... new Set(data)])
    // Normal
    const fun=(arr)=>{
    return arr.filter((val,index)=>arr.indexOf(val)===index)
    }
    console.log(fun(data))

- Remove falsy values
    const data=[42, "everything", "", 2, false, "everything"]
    const fun=(arr)=>{
    return arr.filter((val,index)=> val)
    }
    console.log(fun(data))
    
- truncate a string
    const data='Absolute victory'

    const fun=(n)=>{
        return data.slice(0,n).toString()
    }
    console.log(`${fun(3)}...`)