<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv_l3nbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv_l3nbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wine-alt-filled" {...props}></Icon>
