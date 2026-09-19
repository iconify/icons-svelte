<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgfy970-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wgfy970-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:table-add" {...props}></Icon>
