<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv675zbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gv675zbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:signpost-split" {...props}></Icon>
