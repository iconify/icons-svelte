<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz0lrob5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fz0lrob5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:totem-mask" {...props}></Icon>
