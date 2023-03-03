<h1>
    This is a component  ;)
    <div id='serchbr'>
        <button id="mnu">menu</button>
        <input type="text" id="paths">
    </div>
</h1>


<style>
    h1 {
        font-size: x-large;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-weight: lighter;
        color: aliceblue;
        width: 100%;
        height: 2rem;
    }
    #serchbr {
        padding: 0.5rem;
        display: flex;
        flex-direction: row;
        align-items: space-between;
        border-width: 4px ;
        border-color: white;
        border-radius: 80px;
    }
    #paths {
        size: 4rem;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-weight: lighter;
        border-radius: 0px;
        text-align: rtl;
        padding-inline: 20px;
    }
    #mnu {
        align-self: flex-start;
    }
</style>