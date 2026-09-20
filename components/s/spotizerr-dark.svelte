<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roh82d3sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="roh82d3sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spotizerr-dark" {...props}></Icon>
