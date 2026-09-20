<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrq4i1bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="yrq4i1bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sync" {...props}></Icon>
