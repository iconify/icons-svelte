<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8aj_0y_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8aj_0y_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-2-none-fill" {...props}></Icon>
