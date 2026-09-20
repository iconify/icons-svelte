<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvnx24cwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnx24cwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-3-line" {...props}></Icon>
