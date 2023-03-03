<script>
    let chad = "https://avatars.githubusercontent.com/u/52636922";
    let tg = "tg_ico.png";
    let vk = "vk.png";
    let github = "github.png";
    let yt = "yt.png"
    let cat = "cat.png"
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@500&display=swap');
    * {
        font-family: 'Open Sans', sans-serif;
    }
    .grid {
        display: grid;
        place-items: center;
        grid-template-areas: 
            "a b c";
    }

    .content {
        margin-top: 2%;
    }

    .avatar {
        border-radius: 50%;
    }
    .center-grid {
        max-width: 600px;
        margin-left: auto;
        margin-right: auto;
        grid-area: b;
    }
    .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
    .contacts {
        display: grid;
        grid-auto-flow: column;
        align-items: center;
        justify-content: center;
        grid-gap: 50px;
    }

    .bio {
        margin-top: 2%;
        font-size: large;
        margin-bottom: 2%;
    }
</style>


<div class = "grid">
    
    <div class="content center-grid">
        <h2 class="center">Greetings! It's UserCommon's home page.</h2>
        <img class="avatar center" src={chad} alt="chad" style="">

        <div class="bio">
            Hi, I'm UserCommon! Currently i'm student and learning programming. I love Rust Programming language and Python! 
        </div>

        <h3>My contacts:</h3>
        <div class="center">
            <div class="contacts">
                <a href="https://t.me/Jerkoffovich"><img alt="my_tg" src={tg} style="max-width: 32px;"></a>
                <a href="https://vk.com/shardoffsky"><img alt="my_vk" src={vk} style="max-width: 32px;"></a>
                <a href="https://github.com/UserCommon"><img alt="my_gh" src={github} style="max-width: 32px;"></a>
                <a href="https://www.youtube.com/channel/UCBnRC66OT6CXLVK1HdeRFWA"><img alt="my_yt" src={yt} style="max-width: 32px;"></a>
                <a href="https://t.me/+3FwbNcsBXs8yNTAy"><img alt="my_tg" src={tg} style="max-width: 32px;"></a>
            </div>
        </div>
    </div>
</div>
