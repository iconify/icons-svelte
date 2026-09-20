<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unlmfen_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unlmfen_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:shapes" {...props}></Icon>
