<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgnvl2rtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnvl2rtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-multiple" {...props}></Icon>
