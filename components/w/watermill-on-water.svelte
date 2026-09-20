<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/creiyz41p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="creiyz41p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:watermill-on-water" {...props}></Icon>
