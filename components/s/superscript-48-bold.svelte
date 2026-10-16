<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9ey6-_v.css';
import '../../css/d/ddxiy4bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vi9ey6-_v"/><path class="ddxiy4bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:superscript-48-bold" {...props}></Icon>
