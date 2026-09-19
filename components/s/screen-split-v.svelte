<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaa3j5mot.css';
import '../../css/z/z8x18kbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="eaa3j5mot"/><path class="z8x18kbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-split-v" {...props}></Icon>
