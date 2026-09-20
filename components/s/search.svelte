<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxm0oqbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxm0oqbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:search" {...props}></Icon>
