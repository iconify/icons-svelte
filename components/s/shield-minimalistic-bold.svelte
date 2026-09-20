<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtxs9fivs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtxs9fivs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-bold" {...props}></Icon>
