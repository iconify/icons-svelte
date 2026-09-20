<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq8bm1t3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eq8bm1t3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:treasure-map-x" {...props}></Icon>
