<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5f-q7ynd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5f-q7ynd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:waveform" {...props}></Icon>
