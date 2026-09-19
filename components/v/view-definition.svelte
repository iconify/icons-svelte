<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh42s1kew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sh42s1kew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-definition" {...props}></Icon>
