<template>
    <div :style={color:$store.state.color} class="contador">
      {{ $store.state.contador }}
    </div>
</template>

<script>

export default {
  name: 'Contador'
}
</script>