<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aat5akb2r.css';
import '../../css/x/xpyjtvwnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aat5akb2r"/><path class="xpyjtvwnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltage-high-20" {...props}></Icon>
