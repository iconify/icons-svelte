<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_r8o4g5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_r8o4g5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:server-network-alt" {...props}></Icon>
