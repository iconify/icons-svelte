<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sci1huwnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sci1huwnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thunderstorm-line" {...props}></Icon>
