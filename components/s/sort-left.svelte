<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vboiq-pvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vboiq-pvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:sort-left" {...props}></Icon>
