+++
title = "Home"
description = "Home site description."
sort_by = "date"
template = "index.html"
page_template = "page.html"
+++

{{ tab_nav_box(
        id = "home"
        class = "mb-5"
        tab_titles = [
            "About",
            "Skills",
            "Contact"
        ]
        tab_contents = [
            "My name is John-Sebastian Nado, I am a programming teacher, software developper and a lover of 'free' software as in freedom.",
            "I have experience in the game development and low level programming.",
            "You can contact me at mundusnine@gmail.com"
        ]
    )
}}