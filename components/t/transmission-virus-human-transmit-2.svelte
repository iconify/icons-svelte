<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ecx8h6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ecx8h6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-human-transmit-2" {...props}></Icon>
