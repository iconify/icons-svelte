<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnqzr1ypb.css';
import '../../css/j/jo6iw5bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pnqzr1ypb"/><path class="jo6iw5bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:search-sparkle-20-bold" {...props}></Icon>
