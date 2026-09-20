<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6p0xmpux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p6p0xmpux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:signature-rtl" {...props}></Icon>
