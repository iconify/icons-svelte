<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knw-0m56b.css';
import '../../css/x/xr22nd2nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knw-0m56b"/><path class="xr22nd2nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:science-filled" {...props}></Icon>
