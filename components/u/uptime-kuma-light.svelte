<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkwa3_bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkwa3_bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptime-kuma-light" {...props}></Icon>
