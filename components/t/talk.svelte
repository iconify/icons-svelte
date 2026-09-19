<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs9g5f4wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hs9g5f4wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:talk" {...props}></Icon>
