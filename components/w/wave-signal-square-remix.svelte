<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts8pgfrda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ts8pgfrda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wave-signal-square-remix" {...props}></Icon>
