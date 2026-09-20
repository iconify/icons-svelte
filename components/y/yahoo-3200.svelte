<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4oj3_btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="k4oj3_btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-3200" {...props}></Icon>
