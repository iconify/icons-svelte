<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u45gazbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="u45gazbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:screen" {...props}></Icon>
