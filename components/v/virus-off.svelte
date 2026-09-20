<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg9h2sbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg9h2sbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:virus-off" {...props}></Icon>
