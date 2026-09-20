<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4_56rbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4_56rbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:scribble-off" {...props}></Icon>
