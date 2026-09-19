<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aukm4obte.css';
import '../../css/r/r8ldhbbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="aukm4obte"/><path class="r8ldhbbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-address" {...props}></Icon>
