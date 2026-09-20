<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux6ajacqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ux6ajacqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tmdb-light" {...props}></Icon>
