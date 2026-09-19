<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoyfc1bhb.css';
import '../../css/l/lqbe3zbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yoyfc1bhb"/><path class="lqbe3zbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tag" {...props}></Icon>
