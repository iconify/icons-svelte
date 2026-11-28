<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2b3r1gbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2b3r1gbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-call-x" {...props}></Icon>
