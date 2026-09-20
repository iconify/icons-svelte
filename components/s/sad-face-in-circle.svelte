<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0t8zkbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u0t8zkbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sad-face-in-circle" {...props}></Icon>
