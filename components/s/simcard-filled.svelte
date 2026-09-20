<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux_f60n2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux_f60n2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:simcard-filled" {...props}></Icon>
