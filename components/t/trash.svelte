<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rllqzd8xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rllqzd8xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:trash" {...props}></Icon>
