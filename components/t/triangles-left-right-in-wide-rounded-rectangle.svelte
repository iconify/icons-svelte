<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7xoccxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sv7xoccxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangles-left-right-in-wide-rounded-rectangle" {...props}></Icon>
