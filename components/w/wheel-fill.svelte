<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc00jxb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc00jxb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wheel-fill" {...props}></Icon>
