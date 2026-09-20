<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt7murb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt7murb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-outline" {...props}></Icon>
