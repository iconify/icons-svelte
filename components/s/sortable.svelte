<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc4novbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vc4novbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:sortable" {...props}></Icon>
