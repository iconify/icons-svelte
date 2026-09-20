<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bei3qrbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bei3qrbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:text-to-speech-fill" {...props}></Icon>
