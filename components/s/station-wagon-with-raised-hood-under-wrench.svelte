<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7am3obid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l7am3obid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon-with-raised-hood-under-wrench" {...props}></Icon>
