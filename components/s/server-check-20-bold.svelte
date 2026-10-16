<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5vx4lykm.css';
import '../../css/i/iwzjusbjd.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5vx4lykm"/><path class="iwzjusbjd"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-check-20-bold" {...props}></Icon>
