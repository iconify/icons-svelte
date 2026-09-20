<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb4whf11f.css';
import '../../css/r/rso40ypgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb4whf11f"/><path class="rso40ypgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shop-sign-open-bold" {...props}></Icon>
