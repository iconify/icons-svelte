<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yldvkm25s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yldvkm25s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toy-brick-remove" {...props}></Icon>
