<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm22dhbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm22dhbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toc" {...props}></Icon>
