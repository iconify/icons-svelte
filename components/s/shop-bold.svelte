<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvjtsyb_r.css';
import '../../css/v/vot5mdwzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvjtsyb_r"/><path class="vot5mdwzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-bold" {...props}></Icon>
