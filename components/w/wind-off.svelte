<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4q568mbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4q568mbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wind-off" {...props}></Icon>
