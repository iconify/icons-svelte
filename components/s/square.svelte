<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we4oo-_ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we4oo-_ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:square" {...props}></Icon>
