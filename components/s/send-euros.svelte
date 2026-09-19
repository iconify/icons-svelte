<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vamp-db2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vamp-db2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:send-euros" {...props}></Icon>
