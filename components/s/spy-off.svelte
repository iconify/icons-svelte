<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcrt57btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcrt57btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:spy-off" {...props}></Icon>
