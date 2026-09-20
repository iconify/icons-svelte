<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st0wm4bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st0wm4bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:shield-ai" {...props}></Icon>
