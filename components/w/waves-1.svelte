<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwwq-4bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="dwwq-4bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:waves-1" {...props}></Icon>
