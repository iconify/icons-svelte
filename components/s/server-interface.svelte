<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox6q4zbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ox6q4zbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:server-interface" {...props}></Icon>
