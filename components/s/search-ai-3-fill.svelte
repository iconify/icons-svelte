<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1--lvb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1--lvb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-3-fill" {...props}></Icon>
