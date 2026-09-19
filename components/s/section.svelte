<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-g_2jb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="u-g_2jb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:section" {...props}></Icon>
