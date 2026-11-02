<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjfa6i3ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjfa6i3ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-flash-line" {...props}></Icon>
