<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nch6exbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nch6exbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:tumblr-solid" {...props}></Icon>
