<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzgbc4l5y.css';
import '../../css/q/qebutnwnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="uzgbc4l5y"/><path class="qebutnwnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:volume-strike" {...props}></Icon>
