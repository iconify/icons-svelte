<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_miccqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh_miccqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:trezor" {...props}></Icon>
