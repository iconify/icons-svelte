<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovqg_nbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovqg_nbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:waveform-sparkle-round" {...props}></Icon>
