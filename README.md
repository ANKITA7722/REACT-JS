Date:-21/09/2024
Day:-Saturday


:-css Slyling

const App=()=>{
    return(
    <>
    <h1 style={{color:"red",
        textDecoration:"underline",fontFamily:"arial"}}>
        Welcome !!!</h1>

        <h2 style={{color:"green",
        textDecoration:"Wevy",fontFamily:"verdana"}}>
        We are Developer!!!</h2>

        <h3 style={{color:"blue",
        textDecoration:"underline",fontSize:"20px"}}>
        Hellow Cybrom !!!</h3>
    
    </>
    )
}
export default App;

2nd Mathode:-

const data={
    color:"green",
        textDecoration:"underline",
        fontFamily:"arial",
        background:"pink"
    }

const App=()=>{
    return(
    <>
    <h1 style={data}>
        Welcome !!!</h1>

    
    </>
    )
}
export default App;
