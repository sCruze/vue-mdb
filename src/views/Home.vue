<template>
  <div>
    <mdb-btn color="primary" rounded>Primary rounded button</mdb-btn>
    <mdb-btn color="default" rounded>Default rounded button</mdb-btn>
    <mdb-btn color="secondary" rounded>Secondary rounded button</mdb-btn>
    <mdb-btn color="success" rounded>Success rounded button</mdb-btn>
    <mdb-btn color="info" rounded>Info rounded button</mdb-btn>
    <mdb-btn color="warning" rounded>Warning rounded button</mdb-btn>
    <mdb-btn color="danger" rounded>Danger rounded button</mdb-btn>
  </div>
</template>

<script>
// @ is an alias to /src
import { mdbBtn } from '@/lib'

export default {
  name: 'Home',
  components: {
    mdbBtn
  }
}
</script>
