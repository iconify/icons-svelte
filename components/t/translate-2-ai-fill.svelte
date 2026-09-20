<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itv_042ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itv_042ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:translate-2-ai-fill" {...props}></Icon>
