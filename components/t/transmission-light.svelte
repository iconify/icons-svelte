<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3rlzx3hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i3rlzx3hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:transmission-light" {...props}></Icon>
