<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoqk-f2dc.css';
import '../../css/a/a-tw93bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqk-f2dc"/><path class="a-tw93bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-cross-bold-duotone" {...props}></Icon>
