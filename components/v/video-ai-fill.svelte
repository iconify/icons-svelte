<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puguj6llg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puguj6llg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-ai-fill" {...props}></Icon>
