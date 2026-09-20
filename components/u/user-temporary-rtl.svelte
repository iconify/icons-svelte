<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7ovgwbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x7ovgwbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-temporary-rtl" {...props}></Icon>
