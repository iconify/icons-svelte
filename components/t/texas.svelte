<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9j73r6gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9j73r6gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:texas" {...props}></Icon>
