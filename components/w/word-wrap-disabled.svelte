<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrishjbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hrishjbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:word-wrap-disabled" {...props}></Icon>
