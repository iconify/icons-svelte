<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiwv_cb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="jiwv_cb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:shuffle" {...props}></Icon>
