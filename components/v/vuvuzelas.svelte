<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd-xe713w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rd-xe713w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vuvuzelas" {...props}></Icon>
