<div class="page">
    <h1>PROGRAMMING</h1>
    <br>
    <div class="codeGrid">
        <div class="cell"><img class="thumbnail"src="codeThumbnails/namesakeThumb.png" alt="This Site Thumbnail">
            <a href="https://github.com/Fireg53/Namesake">This Site</a>
            <div class="icon-row"><i class="fa-brands fa-html5 HTML-icon"></i><i class="fa-brands fa-css CSS-icon"></i><i class="fa-brands fa-square-js JS-icon"></i></div>
        </div>
        <div class="cell"><img class="thumbnail"src="codeThumbnails/visionportal.png" alt="Computer Vision Thumbnail">
            <a href="https://github.com/IFC-Robotics/Center-Stage_2023-2024">Computer Vision</a>
            <div class="icon-row"><i class="fa-brands fa-java Java-icon"></i></div>
        </div>
        <div class="cell"><img class="thumbnail"src="codeThumbnails/summerGame.png" alt="Summer Game Thumbnail">
            <a href="https://github.com/Fireg53/Summer-Game">Summer Game</a>
            <div class="icon-row"><i class="fa-brands fa-html5 HTML-icon"></i><i class="fa-brands fa-css CSS-icon"></i><i class="fa-brands fa-square-js JS-icon"></i></div>
        </div>       
        <div class="cell"><img class="thumbnail"src="codeThumbnails/eventBookerThumb.png" alt="Event Booking Thumbnail">
            <a href="https://github.com/ElliottCepin/event-booking">Event Booking Demo Site</a>
            <div class="icon-row"><i class="fa-brands fa-html5 HTML-icon"></i><i class="fa-brands fa-css CSS-icon"></i><i class="fa-brands fa-square-js JS-icon"></i></div>
        </div>      

    </div>
</div>

<style>
    
    h1 {
        padding-left: 20px;
        color: black;
        text-shadow: grey 1px 1px 2px;
    }
    .page{
        height: calc(100vh - 40px);
        width: calc(100vw - 40px);
        padding: 20px;

    }
    .codeGrid {
        width: 60vw;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content:space-between;
        margin-left: 10vw;
    }
    
    .cell {
        --divider-width: 2px; /* width of line between thumbnail and text */
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        background-color: white;
        position: relative;
        margin: 20px;
        z-index: 0;
        border: 4px solid #4c286a;
        border-radius: 10px;
        box-shadow: 3px 3px 10px;
    }

    /* for rounded border */
    .cell::after {
        content:"";
        width: 300px;
        height: 180px;
        position: absolute;
        border: 4px solid #4c286a;
        border-bottom-width: var(--divider-width);
        border-radius: 10px 10px 0px 0px;
        left: -4px;
        top: -4px;
        z-index: 1;
    }

    .thumbnail {
        width: 300px;
        height: 180px;
        margin-bottom: var(--divider-width);
    }

    a {
        color: var(--template-purple);
        padding-top: 10px;
        padding: 5px;

    }
    a:not(.deactivated):hover {
        text-decoration: underline;
    }

    .icon-row > i{
        margin: 3px;
        font-size: 20px;
    }

    .HTML-icon {
        color: red;
    }

    .CSS-icon {
        color: blue;
    }
    
    .JS-icon {
        color:yellow; 
        box-shadow: 
            inset white -1px -3px, 
            inset white 2px 2px, 
            inset black -10px -10px;
    }

    .Java-icon {
        color: darkred;
    }

    @media screen and (max-width: 1160px) {
        h1 {
            margin-top: 14rem;
            text-align: center;
        }
        .codeGrid {
            width: 100%;
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content:space-around;
            align-items: center;
            margin-left: 0;
        }
    }
</style>