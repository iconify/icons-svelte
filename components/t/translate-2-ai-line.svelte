<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4fxs5usg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4fxs5usg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:translate-2-ai-line" {...props}></Icon>
