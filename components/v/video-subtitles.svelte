<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk6fb0u6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk6fb0u6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:video-subtitles" {...props}></Icon>
