<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svgx0q8ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="svgx0q8ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:water-15" {...props}></Icon>
