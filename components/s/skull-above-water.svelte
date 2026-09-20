<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc-0318zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oc-0318zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skull-above-water" {...props}></Icon>
