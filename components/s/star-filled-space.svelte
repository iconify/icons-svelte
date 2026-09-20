<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc44oibdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oc44oibdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:star-filled-space" {...props}></Icon>
