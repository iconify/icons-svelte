<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnp27ng5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xnp27ng5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:south-korea" {...props}></Icon>
