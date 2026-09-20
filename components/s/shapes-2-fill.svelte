<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdpam1rof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdpam1rof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shapes-2-fill" {...props}></Icon>
