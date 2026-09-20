<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwf6w8c0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwf6w8c0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-2-line" {...props}></Icon>
