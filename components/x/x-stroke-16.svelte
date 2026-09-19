<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4iehdv2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t4iehdv2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-stroke-16" {...props}></Icon>
