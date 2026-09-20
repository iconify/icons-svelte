<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8d8c1pjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8d8c1pjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-voice-fill" {...props}></Icon>
