<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdq-b1j7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdq-b1j7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:voice-ai-fill" {...props}></Icon>
