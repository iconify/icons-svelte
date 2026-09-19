<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy2-pue0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fy2-pue0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:tencent-weibo" {...props}></Icon>
