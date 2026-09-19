<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wojym8bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wojym8bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:text-height" {...props}></Icon>
