<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5m23wblo.css';
import '../../css/w/wg0eo9hxf.css';
import '../../css/z/zy2qlf16k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e5m23wblo"/><path class="wg0eo9hxf"/><path class="zy2qlf16k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wireless-charging-20" {...props}></Icon>
