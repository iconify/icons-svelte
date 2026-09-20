<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in6lw_b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="in6lw_b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rustpad-light" {...props}></Icon>
