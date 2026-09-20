<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etfx2dbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="etfx2dbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-tall-rectangles-up" {...props}></Icon>
