<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrb8-hcea.css';
import '../../css/i/i46axmbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrb8-hcea"/><path class="i46axmbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:send-email-envelope-bold" {...props}></Icon>
