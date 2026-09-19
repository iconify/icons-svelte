<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwrw1yo3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwrw1yo3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sparky-bomb" {...props}></Icon>
