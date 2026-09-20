<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iac76_0qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iac76_0qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-voice-line" {...props}></Icon>
