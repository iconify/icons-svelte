<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcgdu8hot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcgdu8hot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:toggl-track" {...props}></Icon>
