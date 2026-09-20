<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1fw_ybgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1fw_ybgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:yelp-logo" {...props}></Icon>
