<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5t9vt_or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n5t9vt_or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:un-link" {...props}></Icon>
