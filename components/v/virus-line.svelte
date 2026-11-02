<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5t-otp0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5t-otp0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:virus-line" {...props}></Icon>
