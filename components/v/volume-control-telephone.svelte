<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuoydbqgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zuoydbqgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:volume-control-telephone" {...props}></Icon>
