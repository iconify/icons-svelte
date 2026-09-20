<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2v24ccdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2v24ccdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:table-density-compact" {...props}></Icon>
