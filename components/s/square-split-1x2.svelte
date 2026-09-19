<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st0_9e3qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="st0_9e3qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-split-1x2" {...props}></Icon>
