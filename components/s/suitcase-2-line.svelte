<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm628pxnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm628pxnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:suitcase-2-line" {...props}></Icon>
