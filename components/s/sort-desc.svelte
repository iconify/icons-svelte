<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrpqgccob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1344};
const content = `<g transform="translate(0 1344) scale(1 -1)"><path class="yrpqgccob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sort-desc" {...props}></Icon>
