<header class="teamTalkHeader">
     <img class="appIcon" src="/AppIcon.svg" alt="TeamTalk icon"/>
     <a href="/"><h1 class="title">TeamTalk</h1></a>
</header>

<style>
   .teamTalkHeader {
        top: 0;
        height: 70px;
        width: 100%;
        background-color: #202020ab;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        font-weight: bold;
        font-size: 20pt;
        padding: 12px;
        position: fixed;
        backdrop-filter: blur(10px); 
   }
   .title {
        transition: all 200ms;
   }
   .title:hover {
        cursor: pointer;
        text-shadow: 0px 0px 20px white;
        color: rgb(255, 255, 255);
        text-shadow: 0 0 20px rgb(173, 56, 252);
   }
   .appIcon {
        width: 50px;
        height: 50px;
        margin-right: 8px;
        transition: all 200ms;
   }
   .appIcon:hover {
        cursor: pointer;
        filter: drop-shadow(0 0 20px rgb(173, 56, 252));
   }
</style>