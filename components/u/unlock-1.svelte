<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u24hh5b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u24hh5b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:unlock-1" {...props}></Icon>
