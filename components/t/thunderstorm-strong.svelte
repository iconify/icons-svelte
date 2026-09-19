<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9jqg7p9p.css';
import '../../css/y/yrb5ix9ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d9jqg7p9p"/><path class="yrb5ix9ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thunderstorm-strong" {...props}></Icon>
