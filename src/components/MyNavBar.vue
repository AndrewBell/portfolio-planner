<template>
  <b-navbar toggleable="sm" type="dark" variant="info">
    <b-navbar-brand href="#">Portfolio Planner</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="https://github.com/AndrewBell/portfolio-planner" target="_blank">GitHub</b-nav-item>
      </b-navbar-nav>
      <b-navbar-nav>
        <b-nav-item href="https://www.recursivechaos.com/" target="_blank">About the Creator</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class MyNavBar extends Vue {}
</script>
