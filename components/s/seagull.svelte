<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpno0acxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpno0acxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:seagull" {...props}></Icon>
