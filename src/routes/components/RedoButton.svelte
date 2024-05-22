<script lang="ts">
  import { redoLastAction } from "../store";
  import iconRotateRight from "$lib/images/icon-rotate-right.svg";
  import ControlButton from "./ControlButton.svelte";

  function onClick() {
    redoLastAction();
  }
</script>

<ControlButton icon={iconRotateRight} label="Redo" {onClick} />
