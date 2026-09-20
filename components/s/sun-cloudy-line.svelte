<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3sal8b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3sal8b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sun-cloudy-line" {...props}></Icon>
