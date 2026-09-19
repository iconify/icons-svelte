<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk1s0nbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xk1s0nbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-cursor" {...props}></Icon>
