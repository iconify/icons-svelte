<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-5ht6mav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-5ht6mav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unwrap" {...props}></Icon>
