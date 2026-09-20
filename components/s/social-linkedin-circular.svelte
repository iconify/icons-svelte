<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_o_vp-2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_o_vp-2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:social-linkedin-circular" {...props}></Icon>
