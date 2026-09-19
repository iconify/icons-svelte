<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0p0d2yta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0p0d2yta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toaster" {...props}></Icon>
