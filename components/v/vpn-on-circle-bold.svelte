<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiz2uy2dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yiz2uy2dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:vpn-on-circle-bold" {...props}></Icon>
