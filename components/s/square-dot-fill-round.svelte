<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xibd44bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xibd44bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dot-fill-round" {...props}></Icon>
