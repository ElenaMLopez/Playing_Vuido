<template>
  <Window title="vuido0" width="400" height="150" margined v-on:close="exit">
    <Box padded>
      <Box horizontal padded>
        <TextInput stretchy></TextInput>
        <Button :enabled="!!query"> Buscar </Button>
      </Box>
    </Box>
  </Window>
</template>

<script>
export default {
  methods: {
    exit() {
      this.$exit();
    }
  }
}
</script>
