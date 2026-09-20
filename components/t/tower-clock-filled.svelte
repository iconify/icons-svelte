<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l37jp9bzw.css';
import '../../css/t/t54c4pnar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l37jp9bzw"/><path class="t54c4pnar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:tower-clock-filled" {...props}></Icon>
