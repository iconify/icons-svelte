<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmd4-hb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zmd4-hb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:time-o" {...props}></Icon>
