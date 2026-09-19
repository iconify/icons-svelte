<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drfiezb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drfiezb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tv-tower" {...props}></Icon>
