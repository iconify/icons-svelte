<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey3ko8bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ey3ko8bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:webhook-round" {...props}></Icon>
