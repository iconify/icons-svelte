<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rab3i_pim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rab3i_pim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smallcaps-filled" {...props}></Icon>
