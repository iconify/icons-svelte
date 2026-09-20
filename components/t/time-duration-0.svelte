<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iycp5mbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iycp5mbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:time-duration-0" {...props}></Icon>
