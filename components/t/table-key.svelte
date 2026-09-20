<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp1x9_euk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp1x9_euk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-key" {...props}></Icon>
