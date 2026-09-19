<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9-rrjd5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z9-rrjd5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-caret-left" {...props}></Icon>
