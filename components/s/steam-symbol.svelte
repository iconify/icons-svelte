<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc5smubsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wc5smubsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:steam-symbol" {...props}></Icon>
