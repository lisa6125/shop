<template lang="pug">
  #app.my-5
    b-container
      b-row
        b-col.text-center.mb-3(cols="12")
          #nav
            router-link(to='/') Home
            | &nbsp;|&nbsp;
            router-link(to='/about') About
            | &nbsp;|&nbsp;
            router-link(to='/cart') Cart
        b-col(cols="12")
          router-view
</template>
