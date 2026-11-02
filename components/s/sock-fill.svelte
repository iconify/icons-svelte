<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gey1e15eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gey1e15eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sock-fill" {...props}></Icon>
