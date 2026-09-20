<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve067lbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ve067lbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:success" {...props}></Icon>
