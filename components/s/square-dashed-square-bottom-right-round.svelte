<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdqmb4bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdqmb4bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-square-bottom-right-round" {...props}></Icon>
