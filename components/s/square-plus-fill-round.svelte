<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg1bm570r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1bm570r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-plus-fill-round" {...props}></Icon>
