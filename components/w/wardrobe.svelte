<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c08ya8vwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c08ya8vwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wardrobe" {...props}></Icon>
