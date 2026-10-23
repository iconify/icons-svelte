<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbb0ayics.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbb0ayics"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ruler-dimension-line" {...props}></Icon>
