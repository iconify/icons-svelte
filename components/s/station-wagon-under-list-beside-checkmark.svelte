<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv878y2jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv878y2jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:station-wagon-under-list-beside-checkmark" {...props}></Icon>
