<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmyot3b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmyot3b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shovel-fill" {...props}></Icon>
