<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjtb_hbpd.css';
import '../../css/v/vu4dv3btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtb_hbpd secondary"/><path class="primary vu4dv3btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-duo" {...props}></Icon>
