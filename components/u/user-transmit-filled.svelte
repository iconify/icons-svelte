<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fex9wbczz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fex9wbczz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-transmit-filled" {...props}></Icon>
