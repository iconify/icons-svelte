<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo1q0dvgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1q0dvgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggle-right-filled" {...props}></Icon>
