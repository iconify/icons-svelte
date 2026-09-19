<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym02-6qjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ym02-6qjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:union-bold" {...props}></Icon>
