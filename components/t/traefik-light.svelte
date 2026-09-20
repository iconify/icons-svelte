<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exm-ov3sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exm-ov3sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traefik-light" {...props}></Icon>
