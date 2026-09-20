<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zro8qtbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zro8qtbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:wifi-outline" {...props}></Icon>
