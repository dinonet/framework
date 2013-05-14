Assumed Markup

    <body>
        <div class="page">
            <header></header>
            <section class="container">
                <div class="inner">
                    <div class="content">
                        <div class="inner">
                            <!-- content goes here -->
                        </div>
                    </div>
                </div>
            </section>
            <footer></footer>
        </div>
    </body>

Notes:
.page ................. | Contains any overflow / offscreen elements
.container ............ | Defines large <section>'s
.container > .inner ... | Non-padded, centered fluid width block with clearfix
.content .............. | A left floating element
.content > .inner ..... | Padded block with clearfix
