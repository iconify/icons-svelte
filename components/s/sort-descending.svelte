<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbx43lh7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbx43lh7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sort-descending" {...props}></Icon>
