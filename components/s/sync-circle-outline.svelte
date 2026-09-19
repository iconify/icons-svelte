<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/c/c2legdcgb.css';
import '../../css/r/r0i4i9brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="c2legdcgb"/><path class="r0i4i9brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:sync-circle-outline" {...props}></Icon>
