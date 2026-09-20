<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb5220baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tb5220baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:sticky-note" {...props}></Icon>
