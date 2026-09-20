<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwn02sbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwn02sbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-filled" {...props}></Icon>
