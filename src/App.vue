<script setup lang="ts">
import { Popover } from "@ark-ui/vue";
</script>

<template>
  <Popover.Root>
    <Popover.Trigger> Click Me </Popover.Trigger>
    <Popover.Positioner>
      <Popover.Content style="border: 1px solid black">
        <p>
          Regular popover content. When this is clicked, the popover will stay
          open.
        </p>
        <p>When clicking the emoji picker below, it'll autoclose.</p>
        <emoji-picker></emoji-picker>
      </Popover.Content>
    </Popover.Positioner>
  </Popover.Root>
</template>
