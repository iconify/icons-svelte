<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yob_hi-cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yob_hi-cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:tag-o" {...props}></Icon>
