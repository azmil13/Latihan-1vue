<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <img src="./assets/logosemen.jpg" height="30" width="40">
        <h1 class="me-auto">Semen Negeri</h1>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">Tentang</NavbarLink>
          <NavbarLink link="#">Kontak</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
