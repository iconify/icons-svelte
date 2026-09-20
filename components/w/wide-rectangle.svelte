<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovfb4w_au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ovfb4w_au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wide-rectangle" {...props}></Icon>
