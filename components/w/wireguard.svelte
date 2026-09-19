<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoa33-y8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoa33-y8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wireguard" {...props}></Icon>
