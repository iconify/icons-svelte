<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip82d1icr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip82d1icr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-check" {...props}></Icon>
