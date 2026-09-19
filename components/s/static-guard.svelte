<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxm5rigwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxm5rigwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:static-guard" {...props}></Icon>
