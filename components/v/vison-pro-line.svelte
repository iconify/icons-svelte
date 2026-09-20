<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gchj467ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gchj467ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vison-pro-line" {...props}></Icon>
