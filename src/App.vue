<template lang="pug">
  #app
    nav.navbar.has-shadow.is-spaced(role='navigation',
                                    aria-label='main navigation')
      .container
        .navbar-brand
          a.navbar-item(href='https://bulma.io')
            img(src='https://bulma.io/images/bulma-logo.png',
                width='112',
                height='28')
          a.navbar-burger.burger(role='button',
                                 aria-label='menu',
                                 aria-expanded='false',
                                 data-target='navbarBasicExample')
            span(aria-hidden='true')
            span(aria-hidden='true')
            span(aria-hidden='true')
        .navbar-end
          a.navbar-item ABOUT
          a.navbar-item PROJECTS
          a.navbar-item CONTACT
    #main
      router-view
</template>

<style lang="sass">
@import 'assets/main.scss'
</style>
