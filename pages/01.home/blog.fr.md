---
title: Accueil
body_classes: 'header-image fullwidth'
child_type: item
content:
    items: '@self.children'
    limit: 10
    order:
        by: date
        dir: desc
    pagination: '1'
override_default_title: Accueil
override_default_desc: 'Blog collaboratif de la communauté des apprenants UX UI - activités digitales'
hero_scroll: false
show_sidebar: true
display_post_summary: false
post_icon: calendar-o
hide_post_date: false
hide_post_taxonomy: false
hide_git_sync_repo_link: false
modular_content:
    items: '@self.modular'
    order:
        by: default
        custom:
            - _important-reminders
            - _unit-preparations
feed:
    description: 'Grav CMS Open Course Hub Description'
    limit: 10
---

