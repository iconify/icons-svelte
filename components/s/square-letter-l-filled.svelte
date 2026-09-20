<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyt6z2bxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyt6z2bxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-l-filled" {...props}></Icon>
