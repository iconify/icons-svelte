<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4p90eukn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w4p90eukn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-timelion" {...props}></Icon>
