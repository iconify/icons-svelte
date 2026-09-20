<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzz2ewbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tzz2ewbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three" {...props}></Icon>
