<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vie_4_2vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vie_4_2vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:rounded-mirror" {...props}></Icon>
