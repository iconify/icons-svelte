<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgcsv3b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgcsv3b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:send-light" {...props}></Icon>
