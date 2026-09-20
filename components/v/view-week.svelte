<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibo4zfbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibo4zfbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-week" {...props}></Icon>
