<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu5z-p6zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gu5z-p6zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:spiral-shape-solid" {...props}></Icon>
