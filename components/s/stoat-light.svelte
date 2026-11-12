<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6er-z6mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6er-z6mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stoat-light" {...props}></Icon>
