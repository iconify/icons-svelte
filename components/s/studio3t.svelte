<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi2gyzb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi2gyzb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:studio3t" {...props}></Icon>
