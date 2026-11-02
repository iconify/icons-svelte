<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py5cczbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py5cczbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thunderstorm-line" {...props}></Icon>
