<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0npvtb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0npvtb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:script-text-play" {...props}></Icon>
