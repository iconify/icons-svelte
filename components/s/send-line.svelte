<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n12-wsb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n12-wsb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:send-line" {...props}></Icon>
