<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx4zb4yjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jx4zb4yjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:toolbox" {...props}></Icon>
