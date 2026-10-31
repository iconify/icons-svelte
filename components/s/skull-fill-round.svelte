<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z33hrsxcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z33hrsxcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skull-fill-round" {...props}></Icon>
