<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9jx0eb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9jx0eb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:waterfall" {...props}></Icon>
