<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk9j6c3hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk9j6c3hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snow-line" {...props}></Icon>
