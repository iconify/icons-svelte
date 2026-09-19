<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz9dst_jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1792};
const content = `<path class="jz9dst_jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:user-group" {...props}></Icon>
