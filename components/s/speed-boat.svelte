<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckqk9g60i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ckqk9g60i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:speed-boat" {...props}></Icon>
