<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_e50nvyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="j_e50nvyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signal-50" {...props}></Icon>
