<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugx8g_87f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugx8g_87f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:square-1" {...props}></Icon>
