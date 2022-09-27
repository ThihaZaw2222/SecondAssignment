# SecondAssignment


const express=require('express');
const app=express()

app.get("/KyawKyaw",(req,res)=>{
res.send("<h1>this is from Kyaw Kyaw</h1>");
})
app.get("/Thiha",(req,res)=>{
res.send("<h2>This is from Thiha</h2>")
})
app.get("/ZawZaw",(req,res)=>{
res.send("<h3>This is from Zaw Zaw</h3>")
})
app.listen(3000,()=>{

    console.log('Start running at: port:3000');
})
