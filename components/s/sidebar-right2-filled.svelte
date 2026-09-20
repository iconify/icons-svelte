<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2_p21wcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2_p21wcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sidebar-right2-filled" {...props}></Icon>
