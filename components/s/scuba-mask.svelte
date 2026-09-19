<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5m7rab3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5m7rab3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:scuba-mask" {...props}></Icon>
