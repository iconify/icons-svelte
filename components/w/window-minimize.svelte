<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc34xcctc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc34xcctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:window-minimize" {...props}></Icon>
