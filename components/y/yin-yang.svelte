<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9lrq2kct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="x9lrq2kct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:yin-yang" {...props}></Icon>
