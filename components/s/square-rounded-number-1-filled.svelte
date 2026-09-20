<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv47dnbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv47dnbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-number-1-filled" {...props}></Icon>
