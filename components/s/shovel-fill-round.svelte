<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrl-mxbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrl-mxbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shovel-fill-round" {...props}></Icon>
