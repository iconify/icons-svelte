<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maqvnbcnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="maqvnbcnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-in-area-filled" {...props}></Icon>
