<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9bdq4btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9bdq4btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:waveform-bulk-round" {...props}></Icon>
