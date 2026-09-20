<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt816lcdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt816lcdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:vip-off" {...props}></Icon>
