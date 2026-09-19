<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivsqt1wng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivsqt1wng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:starfighter" {...props}></Icon>
