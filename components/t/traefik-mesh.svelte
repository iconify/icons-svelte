<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cauiu9xcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cauiu9xcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:traefik-mesh" {...props}></Icon>
