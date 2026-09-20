<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enqxstagc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enqxstagc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-right-line" {...props}></Icon>
