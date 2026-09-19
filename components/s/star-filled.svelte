<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhqi00bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhqi00bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:star-filled" {...props}></Icon>
