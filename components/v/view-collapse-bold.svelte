<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzsbxsbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hzsbxsbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:view-collapse-bold" {...props}></Icon>
