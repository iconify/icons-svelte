<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrdb7tbla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yrdb7tbla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:task-hold" {...props}></Icon>
