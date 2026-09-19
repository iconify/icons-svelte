<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-vehb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cu-vehb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sattelite" {...props}></Icon>
