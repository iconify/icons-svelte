<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll8y8vutm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll8y8vutm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-access-control" {...props}></Icon>
