<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7d1ypbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7d1ypbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-2-fill" {...props}></Icon>
