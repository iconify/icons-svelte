<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvy3c3b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvy3c3b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-touch-finger" {...props}></Icon>
