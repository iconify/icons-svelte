<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6ydnjdqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6ydnjdqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waveform-low-solid" {...props}></Icon>
