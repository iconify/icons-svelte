<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-50j0_4f.css';
import '../../css/u/uj3418bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u-50j0_4f"/><path class="uj3418bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-remove" {...props}></Icon>
