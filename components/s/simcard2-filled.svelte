<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkybv0bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkybv0bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:simcard2-filled" {...props}></Icon>
