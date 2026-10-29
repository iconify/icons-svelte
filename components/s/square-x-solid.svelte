<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2uq3i48e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2uq3i48e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-x-solid" {...props}></Icon>
