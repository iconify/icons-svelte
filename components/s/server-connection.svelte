<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl8nwac8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl8nwac8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:server-connection" {...props}></Icon>
