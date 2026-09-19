<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aukm4obte.css';
import '../../css/z/zu_0t47tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="aukm4obte"/><path class="zu_0t47tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-home" {...props}></Icon>
