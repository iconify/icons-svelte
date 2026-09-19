<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2o51bbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="j2o51bbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sd-card" {...props}></Icon>
