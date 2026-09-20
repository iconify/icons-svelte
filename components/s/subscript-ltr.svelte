<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcnwxeb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mcnwxeb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:subscript-ltr" {...props}></Icon>
