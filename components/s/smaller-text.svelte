<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gufr_knst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gufr_knst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:smaller-text" {...props}></Icon>
