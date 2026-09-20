<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdm1m0bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mdm1m0bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traefik" {...props}></Icon>
