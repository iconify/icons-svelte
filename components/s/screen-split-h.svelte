<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaa3j5mot.css';
import '../../css/w/w0y1bnl1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="eaa3j5mot"/><path class="w0y1bnl1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-split-h" {...props}></Icon>
