<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5hl_xoez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i5hl_xoez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thor-fist" {...props}></Icon>
