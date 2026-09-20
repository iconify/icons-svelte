<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt7sn_o_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt7sn_o_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:signal" {...props}></Icon>
