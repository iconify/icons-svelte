<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhy0hdblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhy0hdblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:siri-line" {...props}></Icon>
