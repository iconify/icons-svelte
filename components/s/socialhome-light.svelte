<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlt9o_vzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zlt9o_vzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:socialhome-light" {...props}></Icon>
