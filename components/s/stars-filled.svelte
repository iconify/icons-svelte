<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiwx514tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwx514tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stars-filled" {...props}></Icon>
