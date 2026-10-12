<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5jbthbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r5jbthbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-circle-stroke-20" {...props}></Icon>
