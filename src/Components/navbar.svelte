<script>
let active = false
</script>
<nav class="navbar" role="navigation" aria-label="main navigation" style="width: 100%; position: fixed; border-bottom: 1px solid;">
    <div class="navbar-brand">
        <a class="navbar-item">
            <strong class="title"> Eduard Faus </strong>
        </a>

        <a role="button" class="navbar-burger" on:click="{() => active = !active}" class:is-active={active} aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
        </a>
    </div>

    <div id="navbarBasicExample" class:is-active={active} class="navbar-menu">
        <div class="navbar-start">
            <a href="#aboutme" class="navbar-item">
                About Me
            </a>
            <a href="#projects" class="navbar-item">
                Projects
            </a>
            <a href="#daysofcode" class="navbar-item">
                100 Days of Code
            </a>
            <a href="#articles" class="navbar-item">
               Articles
            </a>
            <a href="#books" class="navbar-item">
                Books
            </a>
        </div>

        <div class="navbar-end">
            <div class="navbar-item">
                <div class="buttons">
                    <a href="https://github.com/edufaus/portfolio" class="button is-dark">
                        View Code on GitHub
                    </a>
                </div>
            </div>
        </div>
    </div>
</nav>