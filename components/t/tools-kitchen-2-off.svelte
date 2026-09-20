<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny4u_8yny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4u_8yny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tools-kitchen-2-off" {...props}></Icon>
