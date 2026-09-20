<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb8db3bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb8db3bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vivawallet" {...props}></Icon>
