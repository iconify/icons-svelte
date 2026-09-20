<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg42y0jtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gg42y0jtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-move-column-after-ltr" {...props}></Icon>
