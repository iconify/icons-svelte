<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhmi6-ziu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhmi6-ziu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-on-ai-fill" {...props}></Icon>
