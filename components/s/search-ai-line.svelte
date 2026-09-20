<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv1rs9bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv1rs9bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:search-ai-line" {...props}></Icon>
