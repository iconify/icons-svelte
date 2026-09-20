<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib5nucbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib5nucbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stop-linear" {...props}></Icon>
