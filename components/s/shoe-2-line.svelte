<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-upqtxzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-upqtxzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shoe-2-line" {...props}></Icon>
