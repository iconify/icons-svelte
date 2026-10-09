<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxcjxo_wu.css';
import '../../css/x/xtrfu-zjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dxcjxo_wu"/><path class="xtrfu-zjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-right-48-bold" {...props}></Icon>
