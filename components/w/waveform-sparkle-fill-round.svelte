<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bymdhacps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bymdhacps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:waveform-sparkle-fill-round" {...props}></Icon>
