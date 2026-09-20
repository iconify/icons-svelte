<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es3k_-b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es3k_-b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-received-2-fill" {...props}></Icon>
