<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk8k6mbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="dk8k6mbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:traffic-light" {...props}></Icon>
