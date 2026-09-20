<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uunwh0bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uunwh0bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-map-region" {...props}></Icon>
