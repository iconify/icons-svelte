<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yccp5dbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yccp5dbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scroll" {...props}></Icon>
