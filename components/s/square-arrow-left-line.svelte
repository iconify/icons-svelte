<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml4doxj6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml4doxj6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-left-line" {...props}></Icon>
