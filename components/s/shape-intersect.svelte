<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgtr2_73j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jgtr2_73j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shape-intersect" {...props}></Icon>
