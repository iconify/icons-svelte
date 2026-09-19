<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cygib890u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cygib890u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sands-of-time" {...props}></Icon>
