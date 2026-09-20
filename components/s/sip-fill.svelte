<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs-u-bc-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs-u-bc-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sip-fill" {...props}></Icon>
