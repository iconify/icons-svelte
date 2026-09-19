<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnbc61mfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xnbc61mfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:thermometer-cold" {...props}></Icon>
