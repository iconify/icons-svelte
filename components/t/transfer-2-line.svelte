<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2y6cq4at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2y6cq4at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-2-line" {...props}></Icon>
