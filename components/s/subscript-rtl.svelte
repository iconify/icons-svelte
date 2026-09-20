<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ov1c2-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q0ov1c2-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:subscript-rtl" {...props}></Icon>
