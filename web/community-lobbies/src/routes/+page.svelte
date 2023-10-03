<script>
    // todo: optimize this page for mobile
    // todo: on mobile, make the background play the images automatically like a gif, on pc use scroll
</script>

<!--Make a header-->
<header id="nav">
    <!--Logo -->
    <div>
        <h2>Community Lobbies</h2>
        <!--        todo: add the logo to the side of this-->
    </div>
    <nav>
        <ul>
            <!--todo: remove right side margin on mobile and replace with hamburber menu-->
            <li><a href="about">About Us</a></li>
            <li><a href="auth/login">Login</a></li>
        </ul>
    </nav>

    <!--    todo: make this scroll with the page -->
</header>


<body>

<!--Content-->
<div>
    <!--Heading Letters-->
    <div class="content">
        <p> Join </p>
        <p>The Best</p>
        <p> Community</p>
    </div>
</div>

<!--Cards-->
<div>
    <!--todo: add the isometric cards, on scroll make it display 1-2 clips and keep page in same place, after that let them keep scrolling-->
</div>

<!--Scroll Icon-->
<div>
    <!--    todo: add a scroll icon to indicate scrolling down the page-->
</div>

<!--Divider-->
<div>
    <!--    todo: add wavy divider to go to lighter dark color once they scroll-->
</div>

</body>


<style>
    body, header {
        background-color: black;
    }

    h2, a, p, li{
        color: var(--primary-text-color);
        font-family: 'Poppins', 'sans-serif';

    }

    #nav {
        display: flex;
        justify-content: space-between;
        align-items: center;

        & li {
            display: inline-block;
            margin: 0 10px;

            & a {
                text-decoration: none;
                /*    todo: make the links have a line come into existence on hover */
            }

        }
    }

    .content {

        height: 100vh;
        position: absolute;
        top: 0;
        left: 0;
        padding: 50vh 0 0 0;
        margin: 0;

        box-sizing: border-box;

        & p {
            /*todo: position this further down the page*/
            margin: 0;
            font-size: 11vh;
            padding: 1vw;
            line-height: 0.8;
            font-family: 'Bebas Neue', 'sans-serif';
        }

        @media only screen and (max-width: 600px) {

            padding: 45vh 0 0 0;
        }
    }

</style>