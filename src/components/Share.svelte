<style>
    .Share {
        border: 1px solid rgba(219, 219, 219, 1);
        border-radius: 4px;
        background-color: white;
        margin: 0 0 2em 0;
        width: 300px;
        height: 163px;
        position: absolute;
        top: 300px;
        left: 30%;
        z-index: 9;
        padding: 1em;
    }
    .Share-head {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .Share-head h2 {
        font-size: 16px;
    }
    .Share-head i {
        cursor: pointer;
    }
    .Share-content a {
        display: flex;
        align-items: center;
        text-decoration: none;
        color: black;
        font-size: 14px;
        margin: 2em 0 0 0;
    }
    .Share-content i {
        margin: 0 0.5em 0 0;
        font-size: 20px;
    }

    .Share-content .fa-facebook-square {
        color: #3b5998;
    }

    .Share-content .fa-twitter-square {
        color: #00ACEE;
    }

    .Share-content .fa-whatsapp-square {
        color: #25D366;
    }
</style>

<div class="Share">
    <div class="Share-head">
        <h2>Share</h2>
        <i class="fas fa-times-circle" on:click />
    </div>
    <div class="Share-content">
        <a href="https://www.facebook.com/sharer/sharer.php?&u=https://pugstagram.co" target="_blank">
            <i class="fab fa-facebook-square" />
            Share on Facebook
        </a>
        <a href="https://twitter.com/intent/tweet?text=Aprendiendo%20a%20crear%20un%20enlace%20para%20compartir%20en%20Twitter&url=devstagram.com" target="_blank">
            <i class="fab fa-twitter-square" />
            Share on Twitter
        </a>
        <a href="https://api.whatsapp.com/send?&text=Aprendiendo%20a%20crear%20un%20enlace%20para%20compartir%20en%20Whatsapp%20https://devstagram.com/" target="_blank">
            <i class="fab fa-whatsapp-square" />
            Share on Whatsapp
        </a>
    </div>
</div>