<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4-qyw_pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r4-qyw_pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spiky-fish-under-water" {...props}></Icon>
