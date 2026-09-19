<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i84evwbcm.css';
import '../../css/z/zej4k5jhq.css';
import '../../css/q/q9ug-zblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i84evwbcm"/><path class="zej4k5jhq"/><path class="q9ug-zblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:status-change" {...props}></Icon>
