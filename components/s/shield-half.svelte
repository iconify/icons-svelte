<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulvpn3bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulvpn3bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield-half" {...props}></Icon>
