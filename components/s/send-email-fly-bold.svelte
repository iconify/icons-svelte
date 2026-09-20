<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cio1c0bky.css';
import '../../css/a/ave95yb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cio1c0bky"/><path class="ave95yb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:send-email-fly-bold" {...props}></Icon>
