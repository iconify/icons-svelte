<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjjt68bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mjjt68bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vine-flower" {...props}></Icon>
