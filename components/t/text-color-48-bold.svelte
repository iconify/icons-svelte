<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzbcp5bsh.css';
import '../../css/l/lu7edcbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rzbcp5bsh"/><path class="lu7edcbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-color-48-bold" {...props}></Icon>
