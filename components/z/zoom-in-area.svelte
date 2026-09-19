<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgmyvbbuo.css';
import '../../css/q/qmvfbubxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rgmyvbbuo"/><path class="qmvfbubxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:zoom-in-area" {...props}></Icon>
