<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk7cx-bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk7cx-bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:underline-fill-round" {...props}></Icon>
