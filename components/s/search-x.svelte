<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixlrgdmxl.css';
import '../../css/i/ifen1pnqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixlrgdmxl"/><path class="ifen1pnqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:search-x" {...props}></Icon>
