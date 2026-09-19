<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aukm4obte.css';
import '../../css/u/uub_5lb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="aukm4obte"/><path class="uub_5lb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:search-attribtues" {...props}></Icon>
