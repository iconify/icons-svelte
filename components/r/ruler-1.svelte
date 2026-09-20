<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv21ox71h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qv21ox71h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ruler-1" {...props}></Icon>
