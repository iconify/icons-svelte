<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwkm3t4kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qwkm3t4kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:select-circle-area-1-flat" {...props}></Icon>
