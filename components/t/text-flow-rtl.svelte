<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvxhxcb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pvxhxcb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:text-flow-rtl" {...props}></Icon>
