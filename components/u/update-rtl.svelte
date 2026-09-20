<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8y_vccxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h8y_vccxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:update-rtl" {...props}></Icon>
