<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m__u_xbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m__u_xbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:subway-pass" {...props}></Icon>
