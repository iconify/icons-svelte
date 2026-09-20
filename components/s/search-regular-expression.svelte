<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuui8ccfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tuui8ccfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:search-regular-expression" {...props}></Icon>
