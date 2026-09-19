<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv5badiir.css';
import '../../css/e/e5a3g-bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zv5badiir"/><path class="e5a3g-bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-square-filled" {...props}></Icon>
