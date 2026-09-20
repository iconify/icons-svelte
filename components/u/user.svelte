<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu3_yhbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xu3_yhbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:user" {...props}></Icon>
