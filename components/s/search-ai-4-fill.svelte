<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zig9k8bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zig9k8bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-4-fill" {...props}></Icon>
