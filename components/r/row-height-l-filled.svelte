<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-1_xy66d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k-1_xy66d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:row-height-l-filled" {...props}></Icon>
