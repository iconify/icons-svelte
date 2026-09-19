<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db0mmuk2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db0mmuk2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:send-alt-filled" {...props}></Icon>
