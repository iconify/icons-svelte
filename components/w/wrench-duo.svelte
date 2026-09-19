<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4b3ac4nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="n4b3ac4nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wrench-duo" {...props}></Icon>
