<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsvb0obgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bsvb0obgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:star" {...props}></Icon>
