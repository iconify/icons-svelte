<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfr-qx6ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qfr-qx6ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:scanner-bar-code" {...props}></Icon>
