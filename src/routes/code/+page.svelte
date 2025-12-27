<div class="page">
    <h1>Programming</h1>
    <br>
    <div class="codeGrid">
        <div class="cell namesake"><img class="thumbnail"src="namesakeThumb.png"><a href="https://github.com/Fireg53/Namesake">This Site</a></div>
        <div class="cell robotics"><img class="thumbnail"src="eventBookThumb.png"><a href="https://github.com/IFC-Robotics/Center-Stage_2023-2024">Computer Vision</a></div>
        <div class="cell eventBooking"><img class="thumbnail"src="eventBookThumb.png"><a href="https://github.com/ElliottCepin/event-booking">Event Booking Demo Site</a></div>       
    </div>
</div>

<style>
    h1 {
        font-family: "Climate Crisis", sans-serif;
    }
    .page{
        height: 98vh;
        width: 100%;
        background-image: url(paper.png);
        padding: 20px;
    }
    .codeGrid {
        margin-top: 200px;
        display: grid;
        grid-template-columns: auto auto auto;
        margin-left: 20px;
        width: 70vw;
    }
    .page {
        color: white;
        font-family: "Fugaz One", sans-serif;

    }
    a {
        color: #D295BF;
        text-decoration: none;
        padding-top: 10px;
    }
    a:not(.deactivated):hover {
        text-decoration: underline;
    }
    .thumbnail {
        width: 200px;
        height: 100px;
    }
    .cell {
        width: 200px;
        display: flex;
        flex-direction: column;
        outline: 4px solid #E6BCCD;
        align-items: center;
        text-align: center;
        background-color: white;
        position: relative;
        padding: 10px;
        z-index: 1;
        border-radius: 10px;
        
    }

    .cell::after {
        content:"";
        position: absolute;
        background-color: white;
        border-radius: 10px;
        width: 180px;
        left: 0px;
        top: 0px;
        z-index: -1;
    }

</style>