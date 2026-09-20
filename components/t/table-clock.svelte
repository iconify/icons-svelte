<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xerd42b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xerd42b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-clock" {...props}></Icon>
