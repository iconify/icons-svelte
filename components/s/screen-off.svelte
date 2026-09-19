<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr396pfqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zr396pfqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:screen-off" {...props}></Icon>
