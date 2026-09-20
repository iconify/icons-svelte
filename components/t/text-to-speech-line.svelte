<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i174zxb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i174zxb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:text-to-speech-line" {...props}></Icon>
