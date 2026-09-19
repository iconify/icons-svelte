<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxldpx7ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxldpx7ag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-trash-bin" {...props}></Icon>
