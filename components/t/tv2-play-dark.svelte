<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aljiy_w3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aljiy_w3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tv2-play-dark" {...props}></Icon>
