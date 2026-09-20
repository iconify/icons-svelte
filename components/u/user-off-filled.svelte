<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc_r4ms4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc_r4ms4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-off-filled" {...props}></Icon>
