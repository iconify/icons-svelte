<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_bo_ccyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q_bo_ccyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smoke-detector" {...props}></Icon>
