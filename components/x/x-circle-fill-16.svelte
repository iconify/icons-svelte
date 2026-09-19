<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxw1wac_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uxw1wac_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-circle-fill-16" {...props}></Icon>
