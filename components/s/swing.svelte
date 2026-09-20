<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p__2-wbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p__2-wbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:swing" {...props}></Icon>
