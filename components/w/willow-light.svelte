<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfx_zmbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bfx_zmbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:willow-light" {...props}></Icon>
