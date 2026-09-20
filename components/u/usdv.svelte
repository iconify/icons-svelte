<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdpnf5xss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdpnf5xss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:usdv" {...props}></Icon>
