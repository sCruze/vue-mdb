<template>
  <div>
    <mdb-navbar color="indigo" dark>
      <mdb-navbar-brand href="https://mdbootstrap.com/">
        Navbar
      </mdb-navbar-brand>
      <mdb-navbar-toggler>
        <mdb-navbar-nav>
          <mdb-nav-item>22.08.96</mdb-nav-item>
          <mdb-dropdown tag="li" class="nav-item">
            <mdb-dropdown-toggle tag="a" navLink color="indigo" slot="toggle" waves-fixed>Имя пользователя</mdb-dropdown-toggle>
            <mdb-dropdown-menu>
              <mdb-dropdown-item>Action</mdb-dropdown-item>
              <mdb-dropdown-item>Another action</mdb-dropdown-item>
              <mdb-dropdown-item>Something else here</mdb-dropdown-item>
            </mdb-dropdown-menu>
          </mdb-dropdown>
        </mdb-navbar-nav>
      </mdb-navbar-toggler>
    </mdb-navbar>
    <div>
      <mdb-btn color="primary" rounded>Primary</mdb-btn>
      <mdb-btn color="default" rounded>Default</mdb-btn>
      <mdb-btn color="secondary" rounded>Secondary</mdb-btn>
      <mdb-btn color="success" rounded>Success</mdb-btn>
      <mdb-btn color="info" rounded>Info</mdb-btn>
      <mdb-btn color="warning" rounded>Warning</mdb-btn>
      <mdb-btn color="danger" rounded>Danger</mdb-btn>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import { mdbBtn, mdbNavbar, mdbNavbarBrand, mdbNavbarToggler, mdbNavbarNav, mdbNavItem, mdbDropdown, mdbDropdownMenu, mdbDropdownToggle, mdbDropdownItem } from '@/mdbootstrap_vue'

export default {
  name: 'Home',
  components: {
    mdbNavbar,
    mdbNavbarBrand,
    mdbNavbarToggler,
    mdbNavbarNav,
    mdbNavItem,
    mdbDropdown,
    mdbDropdownMenu,
    mdbDropdownToggle,
    mdbDropdownItem,
    mdbBtn
  }
}
</script>
