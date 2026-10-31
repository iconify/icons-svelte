<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e39-0ub8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e39-0ub8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-chevron-double-up-fill-round" {...props}></Icon>
